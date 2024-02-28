<p align="center">
  <img src="https://github.com/Anze/KeyCluCask/blob/main/img/keyclu.png?raw=true" height="128" />
  <h1 align="center">KeyClu for macOS</h1>
</p>

Simple and handy overview of applications shortcuts. Easy to use: just press `⌘` twice and hold to see the list.

![platform:macos  + Intel](https://img.shields.io/badge/platform-macOS%20%20%20+%20Intel-2F3640.svg)
![version:bigsur](https://img.shields.io/badge/requirements-Big%20Sur%2B-337AFF.svg)
![category:productivity](https://img.shields.io/badge/category-productivity-blue.svg)
![license:bsd-3-clause-clear](https://img.shields.io/badge/license-BSD--3--Clause--Clear-orange.svg)

[![github downloads](https://img.shields.io/github/downloads/Anze/KeyCluCask/total.svg?label=github%20downloads)](https://github.com/Anze/KeyCluCask/releases/latest)
[![brew downloads](https://img.shields.io/badge/dynamic/json.svg?url=https://formulae.brew.sh/api/cask/keyclu.json&query=$.analytics.install[%27365d%27].keyclu&label=homebrew%20installs&color=brightgreen)](https://formulae.brew.sh/cask/keyclu)

## Screenshots
![screenshot1](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_1.png)

![screenshot2](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_2.png)

![screenshot3](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_3.png)

## Installation
### Homebrew
To install it using Homebrew, open the Terminal app and type:
```
brew install --cask keyclu
```
### Manual
Download the [latest version](https://github.com/Anze/KeyCluCask/releases/latest) `.dmg`, open it and move the KeyClu app to the Applications folder.

## Permissions
* Required access to `Accessibility API` to operate.
* Preferred to have access to `Notification Center` to provide gentle update notification.

## Basic usage
* Press `⌘` key twice and hold (default) to present shortcuts of current app
* Press `⌘` key and hold (alternative) to present shortcuts of current app

## Features
* Adjustable view
* Support `system`, `light` and `dark` theme
* Persistent panel
* Pause app
* Bookmarking shortcuts
* Hide known shortcuts
* List own shortcuts
* Filter and hightlight shortcuts
* Support 3rd-party integrations

## Integrations
* [CustomShortcuts](https://www.houdah.com/customShortcuts/) to customize shortcuts.
* Other tools like [skhd](https://github.com/koekeishiya/skhd) to change KeyClu activation hotkey:
  - Trigger shortcuts panel by passing `--show-shortcuts` param (action becomes `toggle` when App is paused)
  - Toggle persistent panel by passing `--toggle-persistent` param

## FAQ
### How to open Settings if icon is hidden?
To open Settings window simply launch app again.

### App just crashed!
In case of a crash, please open the issue and provide details, relevant logs, and a brief description of your activities that might leading up to the crash. Check the page [FAQ - KeyClu just crashed](https://github.com/Anze/KeyCluCask/wiki/FAQ#keyclu-just-crashed) for guidance on collecting the necessary information for the issue. Your cooperation will help to resolve issue more effectively.

## Roadmap
Take a look at [KeyClu's Project board](https://github.com/users/Anze/projects/1) to get an idea of what's brewing!

## Privacy Policy
KeyClu collects no personal information nor does use any services for analytics, advertising etc.

## License
KeyClu is released under the BSD-3-Clause-Clear license. See [LICENSE](LICENSE) for details.

## Thanks
* [@wanwindwalker](https://github.com/wanwindwalker) (legacy app icon)
* To all the people who made suggestions and reported bugs

You ❤️ to use KeyClu? Be sure to ⭐ it and maybe support me with caffeine.
