# Pong_Mobile_App
This is a mobile app version of the classic game Pong. Built using Kivy

git clone https://github.com/PatrickWalsh6079/Pong_Mobile_App.git
mkdir environments
cd environments
python3 -m venv my_env
source my_env/bin/activate


Depoying to Android (from Linux)
1. sudo apt-get -y upgrade
2. python3 -V
3. sudo apt-get install -y python3-pip
4. sudo apt-get install build-essential libssl-dev libffi-dev
5. sudo apt-get install -y python3-venv
6. sudo apt update
7. sudo apt install -y git zip unzip openjdk-17-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev
8. pip3 install --upgrade Cython==0.29.36 virtualenv  # the --user should be removed if you do this in a venv
9. export PATH=$PATH:~/.local/bin/
10. pip3 install --user --upgrade buildozer
11. buildozer -v android debug

Deploying to iOS (from MacOS)
1. brew install pkg-config sdl2 sdl2_image sdl2_ttf sdl2_mixer gstreamer autoconf automake
2. python3 -m pip install --upgrade pip virtualenv kivy-ios
3. pip3 install Cython==0.29.36
4. brew install autoconf
5. brew install automake
6. export PATH=$PATH:~/.local/bin/

Download XCode from the App Developer store.
Older OSes can install from https://developer.apple.com/download/all/?q=xcode

7. pip3 install --user --upgrade buildozer
8. buildozer -v ios debug
