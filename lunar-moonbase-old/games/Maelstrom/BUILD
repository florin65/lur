(

  patch_it $SOURCE_CACHE/$SOURCE2 1 &&
  patch_it $SOURCE_CACHE/$SOURCE3 1 &&
  
  sedit 's:(prefix)/games/:(datadir):' configure &&

  default_game_build

) > $C_FIFO 2>&1
