# These two lines gets around a make failure relating to some translation
# character issues. This is temporary and needs to be looked at on the next
# version bump. They are aware of this.
  lupdate -noobsolete src/smplayer.pro &&
  cp src/translations/smplayer_bg.ts src/translations/smplayer_gl.ts &&
# Done

make PREFIX=/usr &&
prepare_install  &&
make PREFIX=/usr install

