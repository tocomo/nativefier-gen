The tool is supposed to make it easier to generate an application from a web site. 

# features
 * creates working desktop files incl. WM_CLASS
 * remembers settings to update/fix the app
 * every file is places under ~/.local

# installation

Install [nativefier](https://github.com/jiahaog/nativefier#installation) first.
```
sudo apt install npm
sudo npm install nativefier -g
```

```
sudo wget -O /usr/local/bin/nativefier-gen https://raw.githubusercontent.com/tocomo/nativefier-gen/master/nativefier-gen
sudo chmod 755 /usr/local/bin/nativefier-gen
```

Check the content of the file if you don not trust the installation process or you just want to know what is does!

# usage examples
```
NAME=google-meet URL=https://meet.google.com nativefier-gen --tray --single-instance --min-width 200 --min-height 200 --zoom 1.1
``` 
