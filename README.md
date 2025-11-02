# LinuxInstallHelper
This script package installs helpful tools on a fresh Linux install. This tool can also help update your system, if you like. 

"installscript" first runs apt update && apt upgrade -y, then prompts you to install the following packages:
Sudo, curl, ffmpeg, wget, ufw, vim, Git (if not already installed), nmap, and Ollama.

Run the command git clone https://github.com/benny01000010/LinuxInstallHelper on your fresh Linux install. Then cd into the LinuxInstallHelper directory, run chmod +x installscript, and finally, run installscript (if logged in as root) or sudo bash installscript (if sudo is already installed and you are logged in as a regular user) to begin the installer!

Courtesy of @benny01000010 on Github. Please feel free to contribute! This repository is currently under development. 
