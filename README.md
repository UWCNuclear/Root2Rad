# Root2Rad
Converts ROOT histograms and matrices to Radware

Old ROOT required, e.g. 6.20 or older

To compile:

      g++ Root2Rad.cxx --std=c++11 `root-config --cflags --libs` -oRoot2Rad

To run:

      ./Root2Rad rootfile.root
