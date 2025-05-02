# audacious-bin
https://github.com/audacious-media-player/audacious
https://github.com/audacious-media-player/audacious-plugins

how to run
extract aud.zip
move pkg/bin/{audtool,audacious} to ~/.bin/ or whaatever local path in $PATH
move pkg/lib/ to ~/.local/lib dirs for lib and share 

cat .bin/aud
export export LD_LIBRARY_PATH=/home/k/.local/lib:$LD_LIBRARY_PATH
audacious "$@"


https://archive.org/details/winampskins



gtk only build with least dependecies possible

