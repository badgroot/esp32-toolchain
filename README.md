# ESP32 ToolChain


#### Enviroment setup on ubuntu-16.04
```
$ sudo apt-get install gcc git wget make libncurses-dev flex bison gperf python python-pip python-setuptools python-serial python-cryptography python-future python-pyparsing python-pyelftools
```
#### Toolchain Setup
ESP32 toolchain for Linux is available for download from Espressif website:
```
#for 64-bit Linux:
$ wget https://dl.espressif.com/dl/x tensa-esp32-elf-linux64-1.2 0-80-g6c4433a-5.2.0.tar.gz
#for 32-bit Linux:
$ wget https://dl.espressif.com/dl/xtensa-esp32-elf-linux32-1.22.0-80-g6c4433a-5.2.0.tar.gz
$ sudo tar -c ${toolchain-path} -xzf filename.tar.gz
```

