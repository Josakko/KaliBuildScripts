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

## Cross building for different arches

When it comes to building to various arches just running `./build.sh` will build for your host arch.

To for example build for x86 from x86_64 you can do this by specifying it:

```sh
./build.sh --arch i386
```

Other arches:

x86: i386
x86_64: amd64
