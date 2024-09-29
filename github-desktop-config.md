### IMPORTANT

See the following links for further updates to Github Desktop for Ubuntu. These are official instructions. (also mentioned by [
fetwar on Nov 3, 2023]([https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1?permalink_comment_id=4747847#gistcomment-4747847](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1?permalink_comment_id=4747847#gistcomment-4747847)))

+ [How to Install](https://github.com/shiftkey/desktop?tab=readme-ov-file#installation-via-package-manager)
+ [Latest Releases](https://github.com/shiftkey/desktop/releases/latest)

For the sake of "maintaining the tradition" here is the updated version.

```bash
# UPDATE (2024-01-24)

## Direct copy-paste from official instrubtions
## Github Desktop for Ubuntu
## Get the @shiftkey package feed
wget -qO - https://apt.packages.shiftkey.dev/gpg.key | gpg --dearmor | sudo tee /usr/share/keyrings/shiftkey-packages.gpg > /dev/null
sudo sh -c 'echo "deb [arch=amd64 signed-by=/usr/share/keyrings/shiftkey-packages.gpg] https://apt.packages.shiftkey.dev/ubuntu/ any main" > /etc/apt/sources.list.d/shiftkey-packages.list'
## Install Github Desktop for Ubuntu
sudo apt update && sudo apt install github-desktop
```

There are other methods mentioned in the comments. Many thanks to their contributions.

+ [Meliyio commented on Dec 9, 2023](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1?permalink_comment_id=4787516#gistcomment-4787516)
+ [phanect commented on Nov 19, 2023](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1?permalink_comment_id=4765666#gistcomment-4765666)
+ [rakkarage commented on Nov 17, 2023](https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1?permalink_comment_id=4764150#gistcomment-4764150)


### Archive

```bash

# UPDATE (2022-11-07): Thanks to Sxvxgee's message, the updated code is as follows

sudo wget https://github.com/shiftkey/desktop/releases/download/release-3.1.1-linux1/GitHubDesktop-linux-3.1.1-linux1.deb
### Uncomment below line if you have not installed gdebi-core before
# sudo apt-get install gdebi-core 
sudo gdebi GitHubDesktop-linux-3.1.1-linux1.deb


# UPDATE (2021-10-18): Thanks to Amin Yahyaabadi's message, the updated code is as follows

#sudo wget https://github.com/shiftkey/desktop/releases/download/release-2.9.3-linux3/GitHubDesktop-linux-2.9.3-linux3.deb
### Uncomment below line if you have not installed gdebi-core before
# sudo apt-get install gdebi-core 
#sudo gdebi GitHubDesktop-linux-2.9.3-linux3.deb

# UPDATE (2021-03-05): Thanks to PaoloRanzi81's comment, the updated code is as follows https://gist.github.com/PaoloRanzi81

#sudo wget https://github.com/shiftkey/desktop/releases/download/release-2.6.3-linux1/GitHubDesktop-linux-2.6.3-linux1.deb
### Uncomment below line if you have not installed gdebi-core before
# sudo apt-get install gdebi-core 
#sudo gdebi GitHubDesktop-linux-2.6.3-linux1.deb

## Initial post
#sudo wget https://github.com/shiftkey/desktop/releases/download/release-2.1.0-linux1/GitHubDesktop-linux-2.1.0-linux1.deb
#sudo gdebi GitHubDesktop-linux-2.1.0-linux1.deb
```
