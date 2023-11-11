# KaliBuildScripts
Unofficial scripts for building kali installer/live image

## Usage
1. Install lb, simple cdd, cdebootstrap, git and curl:

```sh
sudo apt update
sudo apt install git live-build simple-cdd cdebootstrap curl -y
```

2. Clone this repo and then cd in it and build ISO:

```sh
git clone https://github.com/Josakko/KaliBuildScripts.git 
cd KaliBuildScripts

./build.sh
```
## Notes
If you have local (private) kali mirror before running `build.sh` in root dir of this repo run:

```sh
echo "http://{your ip here}/kali" > .mirror

./build.sh
```
