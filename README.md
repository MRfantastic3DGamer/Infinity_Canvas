# Infinity_Canvas

##### It's an app designed for drawing on an infinitely large canvas with the capability of infinite zoom, offering all premium features for all devices on the web.

###### visit [the web app](https://infcanvas.freewebhostmost.com/) to use it online.

#### Folder structure
<!---BETTER_FILES_TREE--> 
```
┏ Infinity_Canvas━━━━━━━━━━━━━━━━━━━━━━━┓
┣commitlint.config.js                   ┃
┣yarn.lock                              ┃
┣┏ public━━━━━━━━━━━━━┓                 ┃
┃┣logo512.png         ┃                 ┃
┃┣index.html          ┃                 ┃
┃┣logo192.png         ┃                 ┃
┃┣infinity_canvas.ico ┃                 ┃
┃┣robots.txt          ┃                 ┃
┃┣manifest.json       ┃                 ┃
┃┗━━━━━━━━━━━━━━━━━━━━┛                 ┃
┣package-lock.json                      ┃
┣better-tree                            ┃
┣LICENSE                                ┃
┣README.md                              ┃
┣┏ src━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┓ ┃
┃┣store.js                            ┃ ┃
┃┣┏ reducers━━━━━━━━━━━┓              ┃ ┃
┃┃┣┏ paper━━━━━━━━┓    ┃              ┃ ┃
┃┃┃┣paperSlice.js ┃    ┃              ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━┛    ┃              ┃ ┃
┃┃┣┏ settings━━━━━━━━┓ ┃              ┃ ┃
┃┃┃┣settingsSlice.js ┃ ┃              ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━━┛ ┃              ┃ ┃
┃┃┣┏ router━━━━━━━━┓   ┃              ┃ ┃
┃┃┃┣routerSlice.js ┃   ┃              ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━┛   ┃              ┃ ┃
┃┃┣┏ library━━━━━━━━┓  ┃              ┃ ┃
┃┃┃┣librarySlice.js ┃  ┃              ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━┛  ┃              ┃ ┃
┃┃┗━━━━━━━━━━━━━━━━━━━━┛              ┃ ┃
┃┣┏ assets━━━━━━━━━━━━━━━━━━━━━━━━━━┓ ┃ ┃
┃┃┣┏ icons━━━━━━━━━━━━━┓            ┃ ┃ ┃
┃┃┃┣tool-arrow.svg     ┃            ┃ ┃ ┃
┃┃┃┣redo.svg           ┃            ┃ ┃ ┃
┃┃┃┣left-arrow.svg     ┃            ┃ ┃ ┃
┃┃┃┣home.svg           ┃            ┃ ┃ ┃
┃┃┃┣info.svg           ┃            ┃ ┃ ┃
┃┃┃┣move.svg           ┃            ┃ ┃ ┃
┃┃┃┣maximize.svg       ┃            ┃ ┃ ┃
┃┃┃┣close.svg          ┃            ┃ ┃ ┃
┃┃┃┣light-mode.svg     ┃            ┃ ┃ ┃
┃┃┃┣eraser.svg         ┃            ┃ ┃ ┃
┃┃┃┣folder.svg         ┃            ┃ ┃ ┃
┃┃┃┣tool-freehand.svg  ┃            ┃ ┃ ┃
┃┃┃┣tool-rectangle.svg ┃            ┃ ┃ ┃
┃┃┃┣undo.svg           ┃            ┃ ┃ ┃
┃┃┃┣trashcan.svg       ┃            ┃ ┃ ┃
┃┃┃┣zoom-out.svg       ┃            ┃ ┃ ┃
┃┃┃┣zoom-in.svg        ┃            ┃ ┃ ┃
┃┃┃┣dark-mode.svg      ┃            ┃ ┃ ┃
┃┃┃┣tool-ellipse.svg   ┃            ┃ ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━━━━┛            ┃ ┃ ┃
┃┃┣┏ vendor━━━━━━━━━━━━━━━━━━━━━━━┓ ┃ ┃ ┃
┃┃┃┣┏ bootstrap━━━━━━━━━━━━━━━━━┓ ┃ ┃ ┃ ┃
┃┃┃┃┣bootstrap-grid.min.css.map ┃ ┃ ┃ ┃ ┃
┃┃┃┃┣bootstrap-grid.min.css     ┃ ┃ ┃ ┃ ┃
┃┃┃┃┗━━━━━━━━━━━━━━━━━━━━━━━━━━━┛ ┃ ┃ ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛ ┃ ┃ ┃
┃┃┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛ ┃ ┃
┃┣index.js                            ┃ ┃
┃┣index.css                           ┃ ┃
┃┣constants.js                        ┃ ┃
┃┣┏ components━━━━━━━━━━━━━━━━┓       ┃ ┃
┃┃┣┏ App━━━━━┓                ┃       ┃ ┃
┃┃┃┣index.js ┃                ┃       ┃ ┃
┃┃┃┗━━━━━━━━━┛                ┃       ┃ ┃
┃┃┣┏ Library━━━━━━━━━━━━━━━━┓ ┃       ┃ ┃
┃┃┃┣styles.module.css       ┃ ┃       ┃ ┃
┃┃┃┣index.js                ┃ ┃       ┃ ┃
┃┃┃┣┏ components━━━━━━━━━━┓ ┃ ┃       ┃ ┃
┃┃┃┃┣┏ PaperListItem━━━━┓ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣styles.module.css ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣index.js          ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┗━━━━━━━━━━━━━━━━━━┛ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┣┏ FolderListItem━━━┓ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣styles.module.css ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣index.js          ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┗━━━━━━━━━━━━━━━━━━┛ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┗━━━━━━━━━━━━━━━━━━━━━┛ ┃ ┃       ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━━━━━━━━━┛ ┃       ┃ ┃
┃┃┣┏ Paper━━━━━━━━━━━━━━━━━━┓ ┃       ┃ ┃
┃┃┃┣styles.module.css       ┃ ┃       ┃ ┃
┃┃┃┣index.js                ┃ ┃       ┃ ┃
┃┃┃┣constants.js            ┃ ┃       ┃ ┃
┃┃┃┣┏ components━━━━━━━━━━┓ ┃ ┃       ┃ ┃
┃┃┃┃┣┏ Palette━━━━━━━━━━┓ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣styles.module.css ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣index.js          ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┗━━━━━━━━━━━━━━━━━━┛ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┣┏ Toolbar━━━━━━━━━━┓ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣styles.module.css ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣index.js          ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┗━━━━━━━━━━━━━━━━━━┛ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┣┏ Info━━━━━━━━━━━━━┓ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣styles.module.css ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┣index.js          ┃ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┃┗━━━━━━━━━━━━━━━━━━┛ ┃ ┃ ┃       ┃ ┃
┃┃┃┃┗━━━━━━━━━━━━━━━━━━━━━┛ ┃ ┃       ┃ ┃
┃┃┃┣helpers.js              ┃ ┃       ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━━━━━━━━━┛ ┃       ┃ ┃
┃┃┣┏ InlineEdit━━━━━━━┓       ┃       ┃ ┃
┃┃┃┣styles.module.css ┃       ┃       ┃ ┃
┃┃┃┣index.js          ┃       ┃       ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━━━┛       ┃       ┃ ┃
┃┃┣┏ ToggleDarkMode━━━┓       ┃       ┃ ┃
┃┃┃┣styles.module.css ┃       ┃       ┃ ┃
┃┃┃┣index.js          ┃       ┃       ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━━━┛       ┃       ┃ ┃
┃┃┣┏ Modal━━━━━━━━━━━━┓       ┃       ┃ ┃
┃┃┃┣styles.module.css ┃       ┃       ┃ ┃
┃┃┃┣index.js          ┃       ┃       ┃ ┃
┃┃┃┗━━━━━━━━━━━━━━━━━━┛       ┃       ┃ ┃
┃┃┗━━━━━━━━━━━━━━━━━━━━━━━━━━━┛       ┃ ┃
┃┣setupTests.js                       ┃ ┃
┃┣reportWebVitals.js                  ┃ ┃
┃┣helpers.js                          ┃ ┃
┃┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛ ┃
┣package.json                           ┃
┣┏ src-tauri━━━━━━━━━━━━━━━┓            ┃
┃┣┏ icons━━━━━━━━━━━━━━━━┓ ┃            ┃
┃┃┣Square150x150Logo.png ┃ ┃            ┃
┃┃┣Square310x310Logo.png ┃ ┃            ┃
┃┃┣Square30x30Logo.png   ┃ ┃            ┃
┃┃┣Square142x142Logo.png ┃ ┃            ┃
┃┃┣icon.png              ┃ ┃            ┃
┃┃┣Square71x71Logo.png   ┃ ┃            ┃
┃┃┣128x128.png           ┃ ┃            ┃
┃┃┣StoreLogo.png         ┃ ┃            ┃
┃┃┣Square107x107Logo.png ┃ ┃            ┃
┃┃┣32x32.png             ┃ ┃            ┃
┃┃┣Square284x284Logo.png ┃ ┃            ┃
┃┃┣Square44x44Logo.png   ┃ ┃            ┃
┃┃┣icon.ico              ┃ ┃            ┃
┃┃┣Square89x89Logo.png   ┃ ┃            ┃
┃┃┣icon.icns             ┃ ┃            ┃
┃┃┣128x128@2x.png        ┃ ┃            ┃
┃┃┗━━━━━━━━━━━━━━━━━━━━━━┛ ┃            ┃
┃┣Cargo.lock               ┃            ┃
┃┣tauri.conf.json          ┃            ┃
┃┣┏ src━━━━━━━━┓           ┃            ┃
┃┃┣commands.rs ┃           ┃            ┃
┃┃┣config.rs   ┃           ┃            ┃
┃┃┣main.rs     ┃           ┃            ┃
┃┃┣file.rs     ┃           ┃            ┃
┃┃┣menu.rs     ┃           ┃            ┃
┃┃┗━━━━━━━━━━━━┛           ┃            ┃
┃┣Cargo.toml               ┃            ┃
┃┣build.rs                 ┃            ┃
┃┗━━━━━━━━━━━━━━━━━━━━━━━━━┛            ┃
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
```