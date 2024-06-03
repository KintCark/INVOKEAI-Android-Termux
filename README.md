# INVOKEAI-Android-Termux
I found out u can also install invokeai on Android yyyeeeaaaaahhhh!!!




pkg updated && pkg upgrade -y && termux-setup-storage &&
pkg install wget -y && pkg install git -y && pkg install proot -y &&
cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh 

STEP1
apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y 

STEP2
apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y
STEP3
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
STEP4
git clone https://github.com/invoke-ai/InvokeAI.git
STEP5
cd InvokeAI
STEP6
cd installer
STEP7
./install.sh.in
STEP8
/root/invokeai/invoke.sh
