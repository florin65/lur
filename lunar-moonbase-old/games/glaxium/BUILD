(

  ./configure  --prefix=/usr        \
               --bindir=/usr/games  &&

  #really ugly build fixes...
  sedit 's:-D_REENTRANT:-DREENTRANT -fpermissive:' Makefile &&
  sedit 's:-lpthread:-lpthread -lstdc++:' Makefile &&

  default_make

) > $C_FIFO 2>&1
