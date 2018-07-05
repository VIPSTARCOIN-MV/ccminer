# ccminer-VIPSTARCOIN
Heavy optimized for Windows, build from Visual Studio 2015, CUDA 9.1.  
Based on gelotus fork of ccminer  
Check the [ccminer](https://github.com/gelotus/ccminer) for additional info and how to build.

Benchmarks for VIPSTARCOIN (sha256d)
------------------------------

2x 1080ti with power-target @70%   -> 2309.11 MH/s  
1x 1080ti with power-target @90%   -> 1278.16 MH/s

How to use
------------------------------

run the following command for solo mining  
ccminer -a vipstar -o http://127.0.0.1:PORT/ -u USERNAME -p PASSWORD


run the following command for pool mining  
ccminer -a vipstar -o stratum+tcp://POOLADDRESS:PORT -u USERNAME.WORKERNAME -p PASSWORD

# Building

Open ccminer.sln in VS2015 and compile, the release archive will be in ./dist folder.
