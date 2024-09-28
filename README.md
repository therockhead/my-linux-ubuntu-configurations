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


GCC/G++ compilers:
-------------------------
**install command:** 

```sudo apt install build-essential```

**check gcc**: 

```gcc --version```

**check g++**: 

```g++ --version```

**compile a C file**: 

``` gcc test.c -o test ```

(-o is used to create a binary test file from the C file named "test.c)

then, **to run the binary file**: ./test (which runs the code in the terminal)

**In case of C++:** all the things same as C but with g++ instead of gcc


c++ 14 build file for sublime (Linux):
--------------------------------------
tools->build system->create new one->paste->save as "c++14.sublime.build"
```

{ C
"cmd" : ["g++ -std=c++14 $file_name -o $file_base_name && timeout 4s ./$file_base_name<inputf.in>outputf.in"], 
"selector" : "source.c",
"shell": true,
"working_dir" : "$file_path"
}
```






