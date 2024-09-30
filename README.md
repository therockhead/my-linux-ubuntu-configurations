UBUNTU LINUX **22.04 LTS JAMMY JELLY FISH**

Basic Config:
--------------
**update**:

```sudo apt-get update```

**to upgrade**: 

```sudo apt-get upgrade```

**gnome-tweaks**: 

```sudo apt install gnome-tweaks -y```

**add to browser extension:** 

```sudo apt install gnome-shell-extensions```

**to install media codecs/extra drivers** ```sudo apt install ubuntu-restricted-extras```

**neofetch-detailed machine info**: ```sudo apt install neofetch htop clang nodejs gcc git```

**access neofetch**: ```neofetch```

**to view system activity monitoring**: ```sudo htop``` 

MINIMIZE WINDOW ON CLICK:
-------------------------
**To activate**: ```gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'```
**To deactivaate**: ```gsettings reset org.gnome.shell.extensions.dash-to-dock click-action```

My Coding Environments Setups: 
------------------------------
https://github.com/therockhead/my-linux-ubuntu-configurations/blob/main/environment%20setup.md

Firewall setups:
----------------
**to check firewall status**: ```sudo systemctl status ufw```

      it will show some dialogues Like below-
      
          ```● ufw.service - Uncomplicated firewall
               Loaded: loaded (/lib/systemd/system/ufw.service; enabled; vendor preset: enabled)
               Active: active (exited) since Sat 2024-09-28 17:33:20 +06; 3h 2min ago
                 Docs: man:ufw(8)
             Main PID: 617 (code=exited, status=0/SUCCESS)
                  CPU: 2ms
          ```
          
**to enable firewall**: ```sudo systemctl enable ufw```

**to install graphical uncomplicated firewall**: ```sudo apt install gufw```

**after installing and turning on the gufw, to check status:** ```sudo ufw status```

**to allow 22/tcp port open**: ```sudo ufw allow 22/tcp```

**to deny 22/tcp port**: ```sudo ufw deny 22/tcp``` (best practice)

**Risks of Leaving Port 22 Open**-

_Brute Force Attacks: Attackers often target port 22 with automated scripts to guess SSH passwords. While Fail2ban can help mitigate this by banning IPs after a number of failed login attempts, it may not stop all attacks, especially if the attacker uses a distributed network of IPs.
Zero-Day Vulnerabilities: Even with protections in place, if a vulnerability in SSH is discovered, having the port open could expose your server to exploitation.
Resource Consumption: High volumes of connection attempts can consume resources and potentially lead to denial-of-service conditions._



Themes:
-------
**Site:** gnome-look.org

Basic Terminal ShortCuts:
-------------------------
cd (change directory) example: cd Desktop/

cd - (to get back to previous directory)

mkdir (to make a directory/folder) example: "mkdir files" creates a folder named "files" in the active directory.

touch  (to create a file) for example: "touch 1.txt" creates 1.txt file in the active directory

ls (to view list of files/folders in a specific directory)

Speed-Up Apps Launch Time:
---------------------------
**command:** ```sudo apt install preload```








