(
source /etc/profile.d/qt3.rc &&
qmake qwtplot3d.pro &&
make &&
prepare_install &&
mkdir -p /usr/include/qwtplot3d/ &&
install include/* -m644 /usr/include/qwtplot3d/ &&
rm /usr/lib/libqwtplot3d.so*
install lib/libqwtplot3d.so.0.2.6 /usr/lib/ &&
ln -s /usr/lib/libqwtplot3d.so.0.2.6 /usr/lib/libqwtplot3d.so.0.2 &&
ln -s /usr/lib/libqwtplot3d.so.0.2.6 /usr/lib/libqwtplot3d.so.0 &&
ln -s /usr/lib/libqwtplot3d.so.0.2.6 /usr/lib/libqwtplot3d.so 
)> $C_FIFO 2>&1
