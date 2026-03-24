# Building
To build Matrix Shuffle you have to have
* C++ compiler (like G++, Clang, etc)
* wxWidgets library
* Boost library
* CMake build system
* Git
Here is how install it on different platforms
## Debian/Ubuntu linux
Here is all easy, you just have to write this to install libraries and software for building
```
sudo apt-get install g++
sudo apt-get install cmake
sudo apt-get install libwxgtk3.2-dev
sudo apt-get install git
sudo apt-get install libboost-all-dev
```
After you have to clone repository, and build it using this commands
```
git clone https://github.com/MatrixShuffle/MatrixShuffle.git
cd MatrixShuffle
mkdir Build
cd Build
cmake ..
make
```
Done :D
## Windows (When im wrote this tutorial im used Windows 10 Home edition)
There is much harder.
We recomend to use scoop to install software for building.

For first you have to go on official scoop website, and install it using Windows Powershell. After you have to write this in Powershell
```
scoop install git
scoop install cmake
scoop install gcc
```
After tutorial doesnt completed
