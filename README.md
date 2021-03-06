<h1 align="center"><img src="http://wexond.nersent.tk/logo/wexond.png" width="400"></h1>

[![discord](https://discordapp.com/api/guilds/307605794680209409/widget.png)](https://discord.gg/yAA8DdK)
[![Build Status](https://travis-ci.org/Nersent/Wexond.svg)](https://travis-ci.org/Nersent/Wexond)
[![Standard - JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](http://standardjs.com)
[![dependencies Status](https://david-dm.org/nersent/wexond/status.svg)](https://david-dm.org/nersent/wexond)
[![devDependencies Status](https://david-dm.org/nersent/wexond/dev-status.svg)](https://david-dm.org/nersent/wexond?type=dev)

[![Standard - JavaScript Style Guide](https://cdn.rawgit.com/feross/standard/master/badge.svg)](https://github.com/feross/standard)

# Wexond
Extensible and minimal web browser with material UI made with [`Electron`](https://github.com/electron/electron) and [`React`](https://github.com/facebook/react), that contains many innovative features.

Checkout our [Trello board](https://trello.com/b/dsd7rEEJ/wexond).

## Questions and issues
If you have noticed a bug, please report it on [Github issue tracker](https://github.com/Nersent/Wexond/issues).

## Documentation
Guides and the API reference are located in [`docs`](https://github.com/Nersent/Wexond/tree/refactor/docs).
It also contains documents describing how to use the browser, and create extensions.

## Downloads
[![Downloads](https://img.shields.io/github/downloads/Nersent/Wexond/total.svg)](https://github.com/Nersent/Wexond/releases)

## Running
To run `Wexond` you need to install all needed dependencies using [`npm`](https://docs.npmjs.com/):
```bash
npm install
```
or [`yarn`](https://yarnpkg.com/lang/en/):
```bash
yarn
```

If you have installed all dependencies successfully, then you can run `Wexond` using these methods:
* Standard method
  ```bash
  npm run watch-app
  npm run watch-pages
  npm start
  ```
* Linux
  ```bash
  ./scripts/linux/watch.sh
  ./scripts/linux/start.sh
  ```
* Windows
  
  Just double-click on `scripts/windows/watch.bat` and `scripts/windows/start.bat`
  
These methods are just to help to start the application easier.
They are the same.

## Compiling
* Windows (you must run CMD as administrator).
  ```batch
  npm run compile-all
  ```
  Or Run as administrator `scripts/windows/compile.bat` file.
* Linux
  ```bash
  sudo npm run compile-all
  ```
  
  or
  
  ```bash
  sudo sh scripts/linux/compile.sh
  ```
    
## Screenshots
![Screenshot 1](screenshots/screen1.png)
