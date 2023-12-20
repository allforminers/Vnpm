

This is a Yescrypt, YesPower, Lyra2REv2, CPUpower, power2b, YesPowerSugar, sha256d and more algo mining pool based off of Node Open Mining Portal.


sudo apt-get update && sudo apt-get upgrade -y

apt install git -y

sudo apt install unzip -y

redis-server --daemonize yes

or

npm install multi-hashing 

for dedic

Clone the repository and run `npm update` for all the dependencies to be installed:

```bash
sudo apt-get install build-essential libsodium-dev npm libboost-all-dev libgmp3-dev redis-server -y
sudo apt install nodejs node-gyp libssl1.0-dev -y
sudo apt install npm -y
sudo npm install n -g
sudo n v12
sudo apt purge nodejs npm -y
sudo ln -sf /usr/local/bin/node /usr/bin/node
sudo ln -sf /usr/local/bin/npm /usr/bin/npm
git clone https://github.com/allforminers/Vnpm.git v-nomp
cd v-nomp
npm install
```

**If using Ubuntu 20.04** to install `libssl1.0-dev`
```
sudo nano /etc/apt/sources.list
deb http://security.ubuntu.com/ubuntu bionic-security main
sudo apt update && apt-cache policy libssl1.0-dev
sudo apt-get install libssl1.0-dev -y
```

**If using Ubuntu 22.04** to install `libssl1.0-dev`
```
sudo apt-get install software-properties-common
sudo apt-add-repository -y ppa:rael-gc/rvm
sudo apt-get update
sudo apt-get install rvm
sudo apt install libssl1.0-dev -y

```

```
sudo sed -i 's/bind 127.0.0.1 ::1/bind 127.0.0.1/g' /etc/redis/redis.conf
```
