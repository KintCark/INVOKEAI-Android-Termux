I ACTUALLY GOT IT TO WORK!!! IT USES ONLY 4GB VRAM SO ITS PERFECT FOR HIGH END PHONES!! XD!!! thx to chat gpt for fixing the connection error:)




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
AFTER INSTALLING ALL UBUNTU DEPENDENCIES DOWNLOAD THIS PY3 WHL FILE AND COPY IT TO YOUR TERMUX ROOT FOLDER THEN AFTER YOU COPY IT TO YOUR ROOT TERMUX FOLDER JUST RUN pip install InvokeAI-4.2.3-py3-none-any.whl

GITHUBLINK__________________________________________________________________

https://objects.githubusercontent.com/github-production-release-asset-2e65be/525592995/93df8cdf-7c1d-48e8-b1e5-254bb5afdd8f?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=releaseassetproduction%2F20240603%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240603T173854Z&X-Amz-Expires=300&X-Amz-Signature=316922b6d1da3f84ce0778392300f0357099973dd1669e164c0fe4f19b9e9087&X-Amz-SignedHeaders=host&actor_id=0&key_id=0&repo_id=525592995&response-content-disposition=attachment%3B%20filename%3DInvokeAI-4.2.3-py3-none-any.whl&response-content-type=application%2Foctet-stream

__________________________________________________________________
IF U TRY TO RUN INVOKE AND IT GIVES ERROR DO BELLOW COMMANDS TO FIX IT!!!!

apt-get install nano

nano /etc/hosts

COPY AND PASTE BOTH HOST
127.0.0.1   localhost
::1         localhost

Then Type ctrl+X+Y then enter 
to save and exit then 

invokeai-web

