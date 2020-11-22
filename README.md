# minisheet
**Mini Spreadsheet application**

Run a spreadsheet for simple math to avoid opening Google Docs, Excel, etc... - package as an Electron app, browser extension, etc...

## Run
`yarn start`

## Package as Electron App
#### MacOS
```
electron-packager ./minisheet --platform=darwin --overwrite --asar --icon=[path_to_icon]
```
#### Windows (64bit)
```
electron-packager ./minisheet --platform=win32 --overwrite --asar --icon=[path_to_icon]
```

#### Windows (32bit)
```
electron-packager ./minisheet --platform=win32 --arch=ia32 --overwrite --asar --icon=[path_to_icon]
```
---
## Credits
Spreadsheet code by Ondřej Žára [https://ondras.zarovi.cz](https://ondras.zarovi.cz)

Electron [www.electronjs.org](www.electronjs.org)

