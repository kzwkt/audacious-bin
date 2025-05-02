# audacious-bin
https://github.com/audacious-media-player/audacious
https://github.com/audacious-media-player/audacious-plugins

how to run
extract aud.zip
move pkg/bin/{audtool,audacious} to ~/.bin/ or whaatever local path in $PATH
mv  pkg/bin/audtool ~/.bin/
mv  pkg/bin/audacious ~/.bin/
mv pkg/share/icons/hicolor/scalable/apps/audacious.svg ~/.local/share/icons/
mv pkg/share/applications/audacious.desktop ~/.local/share/applications

edit the audacious.desktop to use aud in exec field


move pkg/lib/ to ~/.local/lib dirs for lib and share 

cat .bin/aud
export export LD_LIBRARY_PATH=/home/k/.local/lib:$LD_LIBRARY_PATH
audacious "$@"

it wont run without plugins
extract aud-plugins.zip
sudo mv -r build/pkg/usr/local/lib/audacious/ /usr/local/lib/
sudo mv -r build/pkg/usr/local/share/ /usr/local/lib/

https://archive.org/details/winampskins

for compressed skin wsz install unzip
sudo apt install unzip -y



gtk only build with least dependecies possible

