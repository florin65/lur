(

  patch_it $SOURCE2 0 &&
  patch_it $SOURCE3 0 &&

  export CFLAGS="$CFLAGS -fPIC" &&

  export DBUS_LIBDIR="/usr/lib/" &&

  default_build

) > $C_FIFO 2>&1
