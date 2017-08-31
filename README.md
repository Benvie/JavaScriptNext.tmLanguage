# JavaScript.tmLanguage
Better JavaScript language definition for TextMate and SublimeText. This builds on the language files commonly used and adds more fine grained matching and also includes new features from ECMAScript 6 like modules, succinct methods, arrow functions, classes, generators, and accessors (ES5).

## Installation and Use

If you haven't already, [install Package Control](https://sublime.wbond.net/installation), then select `JavaScript Next` from the `Package Control: Install Package` dropdown list in the Command Palette.

To set this as your default JavaScript syntax, open a javascript file, then select `View -> Syntax -> Open all with current extension as... -> JavascriptNext`.

You may also need to change the ColorScheme. Pick one from `Preferences -> Color Scheme -> JavaScriptNext`.

## Screenshots

![screenshot](https://raw.github.com/Benvie/JavaScriptNext.tmLanguage/master/screenshots/es6.png)

## Contributing

Edit the yaml files with the `YAML-XXX` extensions, convert them to plist xml files, and send in a pull request. The easiest way to do this is by using [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev). You can do all of the above without leaving sublime text.

YAML is used since it's a lot more compact and easier to edit than xml.