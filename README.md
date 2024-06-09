THIS WORKS ON 8GB RAM!!! DON'T DISABLE PHANTOM PROCESSOR KILLER DOING THIS WILL MAKE ALL STABLE DIFFUSION TERMUX CRASH!!!

pkg updated && pkg upgrade -y && termux-setup-storage &&
pkg install wget -y && pkg install git -y && pkg install proot -y &&
cd ~ && git clone https://github.com/MFDGaming/ubuntu-in-termux.git && cd ubuntu-in-termux && chmod +x ubuntu.sh && ./ubuntu.sh -y && ./startubuntu.sh 


apt update && apt upgrade -y && apt-get install curl git gcc make build-essential python3 python3-dev python3-distutils python3-pip python3-venv python-is-python3 -y &&
apt install gcc musl-dev python3-dev -y

apt-get install libgl1 libglib2.0-0 libsm6 libxrender1 libxext6 -y

apt install -y libglib2.0-0 libgl1-mesa-glx

apt install python3-opencv libopencv-dev

pip install pypatchmatch

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

pip install maturin
AFTER INSTALLING ALL UBUNTU DEPENDENCIES DOWNLOAD THIS PY3 WHL FILE AND COPY IT TO YOUR TERMUX ROOT FOLDER THEN AFTER YOU COPY IT TO YOUR ROOT TERMUX FOLDER JUST RUN pip install InvokeAI-4.2.4-py3-none-any.whl


IF U TRY TO RUN INVOKE AND IT GIVES ERROR DO BELLOW COMMANDS TO FIX IT!!!!

apt-get install nano

nano /etc/hosts

COPY AND PASTE BOTH HOST
127.0.0.1   localhost
::1         localhost

Then Type ctrl+X+Y then enter 
to save and exit then 

invokeai-web





YOU NEED THIS TERMUX MOD VERSION THIS IS THE ONE I USED!


https://github.com/KitsunedFox/termux-monet


