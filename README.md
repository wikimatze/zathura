# zathura

The description under <https://wikimatze.de/vimtex-the-perfect-tool-for-working-with-tex-and-vim/> works not on latest Ubuntu machine - because synctex and zathura-pdf-poppler are for what reasons not compilable anymore.

```
wm~  % find /usr/ -name "*.pc" | grep synctex
/usr/lib/x86_64-linux-gnu/pkgconfig/synctex.pc
```

If you don't have this file anymore on your machine, then my suggestion is to take those binaries (zathura 0.3.8 and pdf-poppler 0.2.8) and copy them to the right folder.
```


## Installation


```
git clone https://github.com/wikimatze/zathura.git ~/git/zathura
```


```
sudo mkdir /usr/lib/zathura

cd ~/git/zathura

sudo cp pdf.so /usr/lib/zathura/

sudo cp zathura /usr/local/bin

```


Check rights:


```
-rwxr-xr-x 1 root root 25376 Aug 19 12:04 /usr/lib/zathura/pdf.so
wm~  % ls /usr/bin/zathura -la
-rwxr-xr-x 1 root root 301352 Aug 19 12:11 /usr/bin/zathura
```





