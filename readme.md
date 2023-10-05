<p align="center">
  <img src="https://github.com/Anze/KeyCluCask/blob/main/img/keyclu.png?raw=true" height="128" /> 
  <h1 align="center">KeyClu for macOS</h1>
</p>

Simple and handy overview of all shortcuts for applications. Easy to use: just press `⌘` twice and hold to see the list.

![platform:macos  + Intel](https://img.shields.io/badge/platform-macOS%20%20%20+%20Intel-2F3640.svg)
![version:bigsur](https://img.shields.io/badge/requirements-Big%20Sur%2B-337AFF.svg)
![category:productivity](https://img.shields.io/badge/category-productivity-blue.svg)
![license:bsd-3-clause-clear](https://img.shields.io/badge/license-BSD--3--Clause--Clear-orange.svg)

[![github downloads](https://img.shields.io/github/downloads/Anze/KeyCluCask/total.svg?label=github%20downloads)](https://github.com/Anze/KeyCluCask/releases/latest)
[![brew downloads](https://img.shields.io/badge/dynamic/json.svg?url=https://formulae.brew.sh/api/cask/keyclu.json&query=$.analytics.install[%27365d%27].keyclu&label=homebrew%20installs&color=brightgreen)](https://formulae.brew.sh/cask/keyclu)

## Screenshots
![screenshot1](https://github.com/Anze/KeyCluCask/blob/main/img/screenshot_1.png?raw=true)

![screenshot2](https://github.com/Anze/KeyCluCask/blob/main/img/screenshot_2.png?raw=true)

## Installation
### Homebrew
To install it using Homebrew, open the Terminal app and type:
```
brew install --cask keyclu
```
### Manual
Download the [latest version](https://github.com/Anze/KeyCluCask/releases/latest) `.dmg`, open it and move the KeyClu app to the Applications folder.

## Required Permissions
* Required access to `Accessibility API` to operate.
* Preferred to have access to `Notification Center` to provide gentle update notification.

## Usage
* Press `⌘` key twice and hold (default) to present shortcuts of current app
* Press `⌘` key and hold (alternative) to present shortcuts of current app
* Press `⌘` key 3 times to toggle persistent panel

## Features
* Adjustable view
* Support `system`, `light` and `dark` theme
* Bookmarking shortcuts
* Pause app
* Persistent panel
* Register own shortcuts
* Support 3rd-party integrations
  
### Integrations
* [CustomShortcuts](https://www.houdah.com/customShortcuts/) to customize shortcuts.
* Other tools like [skhd](https://github.com/koekeishiya/skhd) to change KeyClu activation hotkey:
  - Trigger shortcuts panel by passing `--show-shortcuts` param (action becomes `toggle` when App is paused)
  - Toggle persistent panel by passing `--toggle-persistent` param

## FAQ
### How to open Settings if icon is hidden?
To open Settings window simply launch app again or quickly press `⌃`(control) key 3 times.

## Privacy Policy
KeyClu collects no personal information nor does use any services for analytics, advertising etc.

## License
KeyClu is released under the BSD-3-Clause-Clear license. See [LICENSE](LICENSE) for details.

## Thanks
* [@wanwindwalker](https://github.com/wanwindwalker) (app icon)
* To all the people who made suggestions and reported bugs

You ❤️ to use KeyClu? Be sure to ⭐ it and maybe support me with caffeine.
