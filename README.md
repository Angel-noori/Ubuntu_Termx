# Ubuntu_Termx
Install Ubuntu in your termux without a rooted device and make Device rooted by Termux


<div align="center">

 [![Instagram](https://img.shields.io/badge/Instagram-0A0A0A?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/fariha_nazii/)
 [![Telegram](https://img.shields.io/badge/Telegram-0A0A0A?style=for-the-badge&logo=Telegram&logoColor=white)](https://www.telegram.me/Opleech_updates/)
</div>

## What's This?

This is a script that allows you to install Ubuntu in your termux application without a rooted device

## Updates

**• Updated to ubuntu 22.04**

## Important

**• If you have to use ubuntu in termux with a x86/i\*86 architecture or prefer ubuntu 19.10 you can use this branch -> https://github.com/Angel-noori/Ubuntu_Termx/tree/ubuntu18.04**

**• If you get an error message that says "Fatal Kernel too old" you have to uncomment the line that reads "command+=" -k 4.14.81"" (remove the # that is located in front of the line) in the "startubuntu.sh" file**

### Installation steps

1. Update termux: `apt-get update && apt-get upgrade -y`
2. Install wget: `apt-get install wget -y`
3. Install proot: `apt-get install proot -y`
4. Install git: `apt-get install git -y`
5. Go to HOME folder: `cd ~`
6. Download script: `git clone https://github.com/Angel-noori/Ubuntu_Termx.git`
7. Go to script folder: `cd ubuntu-in-termux`
8. Give execution permission: `chmod +x ubuntu.sh`
9. Run the script: `./ubuntu.sh -y`
10. Now just start ubuntu: `./startubuntu.sh`
