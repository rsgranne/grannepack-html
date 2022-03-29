# Changelog

All notable changes to the "grannepack-html" extension pack will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [0.6] - 2022-03-29

Replaced the [Spell Right](https://marketplace.visualstudio.com/items?itemName=ban.spellright) extension with [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker), which does a far better job & is certainly better for code. Please note that Code Spell Checker is case insensitive, so it cannot tell the difference between *foo* & *Foo*.

Removed [Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete) because it kept showing duplicate folders & files, & the solutions provided by the extension author didn’t work. And on top of that, I didn’t notice that Microsoft added this same feature, called HTML Path Completion, back in February 2018.

I have updated the [settings.json file I provide](https://gist.github.com/rsgranne/98c3040953a83d8d3cec41b8c058a0ae) to reflect the above changes.

Finally, I updated the README to reflect these changes, & also updated the instructions for using my `settings.json` file.

Total count: 11 extensions & 2 themes.

## [0.5.1] - 2022-01-29

I forgot to add [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server) to `package.json`, so that silly mistake is now fixed.

Total count: 13 extensions & 2 themes.

## [0.5] - 2021-07-14

Removed the following extension, because Microsoft now offers the equivalent with Live Preview:

* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer): see changes to your webpages as you update your code

Added the following extension by Microsoft, which replaces Live Server:

* [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server): hosts a local server in your workspace for you to preview your webpages

Total count: 12 extensions & 2 themes.

## [0.4] - 2020-04-09

Removed the following extensions:

* Auto Rename Tag by Jun Han (as of VS Code 1.44, the functionality, called *Synced Regions*, is built in & detailed at <https://code.visualstudio.com/updates/v1_44#_synced-regions>)

## [0.3] - 2019-11-08

Removed the following extensions:

* expand-region by Le Trieu (the built-in Emmet commands `Emmet: Balance (outward)` & `Emmet: Balance (inward)` perform this function; I recommend adding a key command like `Alt+W` for `Emmet: Balance (outward)` & `Shift+Alt+X` for `Emmet: Balance (inward)`)
* Sort Lines by Tyriar (now built in to Visual Studio Code)

Total count: 13 extensions & 2 themes.

## [0.2] - 2019-05-28

* Fixed numbering & date in CHANGELOG.md.
* Updated links to other GrannePacks in README.md.

## [0.1] - 2019-05-28

Initial release, with 15 extensions & 2 themes.
