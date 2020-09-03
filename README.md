# Root2Rad
Converts ROOT histograms and matrices to Radware

To compile:
g++ Root2Rad.cxx --std=c++11 `root-config --cflags --libs` -oRoot2Rad

To run:
./Root2Rad rootfile.root
