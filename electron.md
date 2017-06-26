# Building Applications with Electron

[@walterg2](https://twitter.com/walterg2) / [github.com/walterg2](https://github.com/walterg2)

## Electron

* Chromium's Content Module (subset of Chrome renderer)
* Almost equal with Chromium's updates
* Good rendering engine!
* NodeJS (V8) back-end.
* Kept up to date within Electron
* ES6!

## Project

* Best practice tree structure:
  ```
  - app
    - main (backend)
    - renderers (frontend)
      - views
  ```
* Don't install Electron globally -- dev deps
* `npm start` == `electron .`
* `let mainWindow` in global scope; `mainWindow = null` when done
* `electron-packager . --all --overwrite` to package it
* Must install WINE for building Win on OSX
* Install electron-packager globally and `save-dev`

## Misc

* Possible conflicts with libs, e.g. `$` in jQuery or RequireJS `define()`.
* "remote" module for the renderer to access the main (backend) process API.
