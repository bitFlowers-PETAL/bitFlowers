
![Image of bitFlowers Logo](https://bit-flowers.com/images/github_header.png)
-----------------
# *bitFlowers* (PETAL) 
# The eGift Cryptocurrency
-----------------
### **Socials** 

Main Website:
https://bit-flowers.com/

Discord:
https://discord.gg/nxGju4nMb3

Github: 
https://github.com/bitFlowers-PETAL/bitFlowers

Explorers:
https://explore.bit-flowers.com/
https://explore2.bit-flowers.com/

Twitter:
https://twitter.com/eFlower_power

Telegram:
https://t.me/bitFlowers

Facebook:
https://www.facebook.com/bitflowersofficial

Medium:
https://medium.com/@iCryptony

Reddit:
http://reddit.com/r/bitFlowers/

-----------------
### **To build on Linux (Ubuntu 18.04)** 
-----------------

If you are unfamiliar with building a coin project from a github repo on a Linux virtual machine, this video below (click link) will guide you with this process. It is important to isolate a build environment on a virtual machine, so that the dependencies do not intefere with your primary OS. Once you have completed the guide, you can move on to the *bitFlowers* build process. 

https://www.youtube.com/watch?v=ThsxqznrgCw

-----------------

#### *1. Installing dependencies* 
-----------------
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3 -y 
sudo apt-get install software-properties-common -y
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install libdb4.8-dev libdb4.8++-dev -y
sudo apt-get install libminiupnpc-dev -y
sudo apt-get install libzmq3-dev -y
sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler -y
sudo apt-get install libqt4-dev libprotobuf-dev protobuf-compiler -y
sudo apt-get install libqrencode-dev -y
sudo apt-get install libboost-all-dev -y
sudo apt-get install libssl1.0 -y
sudo apt-get install qtcreator
sudo apt-get install build-essential libgl1-mesa-dev
sudo apt install git
git clone https://github.com/bitFlowers-PETAL/bitFlowers

-----------------

#### *2. Compiling* 

-----------------

#### **go to repo directory**

qmake bitFlowers-qt.pro
make clean
make 

-----------------

#### **to compile the daemon**

go to repo > src
sudo make -f makefile.unix USE_UPNP=1

-----------------

#### *3. Running the bitFlowers core wallet* 

-----------------

#### **to run**

./bitFlowers-qt

-----------------

#### *For alternative binaries, see:*

bitFlowers/docker/README.md

-----------------

#### *inquiries:* info@bit-flowers.com

-----------------








