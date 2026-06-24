(

  patch_it $SOURCE2 1 &&
  ./configure --prefix=/usr --disable-static &&
  make &&
  cd modules &&
  make
  cd .. &&
  prepare_install &&
  make install &&
  mkdir -p /mnt/hgfs &&
  install -m700 $SCRIPT_DIRECTORY/mount-vmware /etc/init.d/

) > $C_FIFO 2>&1
