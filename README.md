# qtlfs

https://yadi.sk/d/iuXIMlq1GOnDSg

cd qtbase

mkdir build

cd build

../configure  --prefix=/opt/qt5
make;make install




cd qtwebengine                              need 15G swap for link

mkdir build;cd build;qmake ..;make;make install

dd if=/dev/zero of=swapfile bs=1M count=1000      (1Gb)
mkswap swapfile
swapon swapfile


