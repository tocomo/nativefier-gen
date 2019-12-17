
# features
 * creates working desktop files incl. WM_CLASS
 * remembers settings to update/fix the app
 * every file is places under ~/.local

# installation

```
sudo wget -o /usr/local/bin/native-gen https://raw.githubusercontent.com/tocomo/nativefier-gen/master/nativefier-gen
sudo chmod 755 /usr/local/bin/native-gen
```

Check content of file if you dont trust the installation process or you just want to know what is does!

# usage examples
```
NAME=google-meet URL=https://meet.google.com nativefier-gen --tray --single-instance --min-width 200 --min-height 200 --zoom 1.1
``` 
