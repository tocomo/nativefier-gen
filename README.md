
# features
 * creates working desktop files
 * remembers settings to update/fix the app
 * every file is places under ~/.local

# installation

```
sudo wget -o /usr/local/bin/native-gen https://raw.githubusercontent.com/tocomo/nativefier-gen/master/nativefier-gen
```

Check content of file if you dont trust the installation process or you just want to know what is does!

# usage examples
```
NAME=slack URL=https://app.slack.com/client/T1MMBRRUH/unreads nativefier-gen --tray --single-instance --min-width 200 --min-height 200 --zoom 1.1
``` 
