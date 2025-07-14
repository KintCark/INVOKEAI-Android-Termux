THIS WORKS ON 8GB RAM!!!

pkg update -y && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu22/ubuntu22.sh -O ubuntu22.sh && chmod +x ubuntu22.sh && bash ubuntu22.sh

apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y &&
apt install gcc musl-dev python3-dev -y

apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y

apt install -y libglib2.0-0 libgl1-mesa-glx

apt install python3-opencv libopencv-dev

pip install pypatchmatch

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh


pip install maturin

After installation of all the above type logout then force close termux then reopen termux 

cd ubuntu-in-termux && ./startubuntu.sh

source $HOME/.cargo/env


then do next instructions 


DOWNLOAD INVOKEAI INSTALLER ZIP FROM LATEST RELEASES EXTRACT IT THEN MOVE IT TO THE TERMUX UBUNTU ROOT FOLDER THEN CD INTO INVOKEAI INSTALLER FOLDER THEN DO chmod +x install.sh THEN ./install.sh THEN INSTALL EVERYTHING IT TELLS YOU AND MAKESURE YOU PICK CPU.


IF U TRY TO RUN INVOKE AND IT GIVES ERROR DO BELLOW COMMANDS TO FIX IT!!!!

apt-get install nano

nano /etc/hosts

COPY AND PASTE BOTH HOST

127.0.0.1   localhost
::1         localhost

Then Type ctrl+X+Y then enter 
to save and exit then 

cd invokeai

'Fix' the issue with Python running in PRoot

export ANDROID_DATA=anything 




./invoke.sh


