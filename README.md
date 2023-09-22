# KaliBuildScripts
Unofficial scripts for building kali installer/live image

## Usage
1. Install lb, simple cdd, cdebootstrap, git and curl:

```
sudo apt update
sudo apt install git live-build simple-cdd cdebootstrap curl -y

git clone https://github.com/Josakko/KaliBuildScripts.git 
```

2. Go into cloned repo and build ISO:

```
cd KaliBuildScripts

./build.sh
```
