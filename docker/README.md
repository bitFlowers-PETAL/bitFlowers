-----------------
### **Compilations Scripts**
-----------------

#### LinuxQT.sh

1. create a VM blank
2. sudo rm /var/lib/apt/lists/lock && sudo rm /var/cache/apt/archives/lock && sudo rm /var/lib/dpkg/lock*
3. sudo apt-get install git -y
4. git clone https://github.com/bitFlowers-PETAL/bitFlowers
5. cd bitFlowers/docker 
6. sudo su
7. ./master.sh
8. Option 1
9. cd bitFlowers/

#### Windows32.sh

1. create a VM blank
2. sudo rm /var/lib/apt/lists/lock && sudo rm /var/cache/apt/archives/lock && sudo rm /var/lib/dpkg/lock*
3. sudo apt-get install git -y
4. git clone https://github.com/bitFlowers-PETAL/bitFlowers
5. cd bitFlowers/docker 
6. sudo su
7. ./master.sh
8. Option 2
9. cd bitFlowers/
10. chmod 777 bitFlowers-qt.exe

#### Windows64.sh

1. create a VM blank
2. sudo rm /var/lib/apt/lists/lock && sudo rm /var/cache/apt/archives/lock && sudo rm /var/lib/dpkg/lock*
3. sudo apt-get install git -y
4. git clone https://github.com/bitFlowers-PETAL/bitFlowers
5. cd bitFlowers/docker 
6. sudo su
7. ./master.sh
8. Option 3
9. cd bitFlowers/
10. chmod 777 bitFlowers-qt.exe

