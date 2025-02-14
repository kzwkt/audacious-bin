# audacious-bin
https://github.com/audacious-media-player/audacious
https://github.com/audacious-media-player/audacious-plugins

how to run
extract both zip
cd bin  
export LD_LIBRARY_PATH=../lib:$LD_LIBRARY_PATH
./audacious

ERROR plugin-load.cc:70 [plugin_load]: /home/k/.local/lib/audacious/Transport/neon.so could not be loaded: libneon.so.27: cannot open shared object file: No such file or directory
ERROR plugin-load.cc:70 [plugin_load]: /home/k/.local/lib/audacious/Input/wavpack.so could not be loaded: libwavpack.so.1: cannot open shared object file: No such file or directory
direct loading winamp wsz skin needs unzip as dependency
https://archive.org/details/winampskins

move to ~/.local dirs for lib and share 
export export LD_LIBRARY_PATH=/home/k/.local/lib:$LD_LIBRARY_PATH
~/.local/bin/audacious


