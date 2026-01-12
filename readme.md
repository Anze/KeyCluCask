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
A few of the things you can do with KeyClu:
* Adjust view to your liking
* Personalize appearance to `system`, `light` and `dark`
* Bookmark shortcuts
* Hide known shortcuts
* Collapsible groups of shorcuts
* Export App's shortcuts to markdown file
* Display macOS hotkeys
* Display skhd hotkeys
* Display own shortcuts

## Integrations
* [CustomShortcuts](https://www.houdah.com/customShortcuts/) to customize shortcuts
* [skhd](https://github.com/koekeishiya/skhd) to list shortcuts, more details on [skhd wiki page](https://github.com/Anze/KeyCluCask/wiki/Integrations-%E2%80%90-skhd)
* CLI params, more details on [CLI params wiki page](https://github.com/Anze/KeyCluCask/wiki/Integrations-%E2%80%90-CLI-params)

## FAQ
### How to open Settings if icon is hidden?
To open Settings simply launch app again.

### App just crashed!
In case of a crash, please open the issue and provide details, relevant logs, and a brief description of your activities that might leading up to the crash. Check the page [FAQ - KeyClu just crashed](https://github.com/Anze/KeyCluCask/wiki/FAQ#keyclu-just-crashed) for guidance on collecting the necessary information for the issue. Your cooperation will help to resolve issue more effectively.

## Roadmap
Take a look at [KeyClu's Project board](https://github.com/users/Anze/projects/1) to get an idea of what's brewing!

Feature requests are always welcome.

## Privacy Policy
KeyClu collects no personal information nor does use any services for analytics, advertising etc.

## License & Credits
KeyClu is released under the BSD-3-Clause-Clear license. See [LICENSE](LICENSE) for details.

This software uses the following open source packages:
* [Sparkle](https://github.com/sparkle-project/Sparkle)
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift)
* [SQLiteMigrationManager.swift](https://github.com/garriguv/SQLiteMigrationManager.swift)
* [JSON.swift](https://github.com/mikezs/Tisander)

## Thanks
* Special thanks to everyone who contributed to getting the KeyClu to the current state
* [@wanwindwalker](https://github.com/wanwindwalker) for legacy app icon

## Support
If you ❤️ the KeyClu and found it useful for your tasks, be sure to ⭐ it and maybe support me with caffeine.
