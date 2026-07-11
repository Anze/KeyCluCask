[English](readme.md) | 简体中文

<p align="center">
  <img src="https://github.com/Anze/KeyCluCask/blob/main/img/keyclu.png?raw=true" height="128" />
  <h1 align="center">KeyClu for macOS</h1>
</p>

KeyClu 是一个简单、顺手的应用快捷键总览工具。使用方式很直接：只要连续按两次 `⌘` 并按住，就能查看当前应用的快捷键列表。

![platform:macos  + Intel](https://img.shields.io/badge/platform-macOS%20%20%20+%20Intel-2F3640.svg)
![version:bigsur](https://img.shields.io/badge/requirements-Big%20Sur%2B-337AFF.svg)
![category:productivity](https://img.shields.io/badge/category-productivity-blue.svg)
![license:bsd-3-clause-clear](https://img.shields.io/badge/license-BSD--3--Clause--Clear-orange.svg)

[![github downloads](https://sergii.tatarenkov.name/keyclu/support/github-downloads.svg)](https://github.com/Anze/KeyCluCask/releases/latest)
[![brew downloads](https://sergii.tatarenkov.name/keyclu/support/brew-downloads.svg)](https://formulae.brew.sh/cask/keyclu)
[![Crowdin](https://badges.crowdin.net/keyclu/localized.svg)](https://crowdin.com/project/keyclu)

## 截图
![screenshot1](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_1.png)

![screenshot2](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_2.png)

![screenshot3](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_3.png)

## 安装
### Homebrew
如果要通过 Homebrew 安装，请打开“终端”应用并输入：
```
brew install --cask keyclu
```
### 手动安装
下载[最新版本](https://github.com/Anze/KeyCluCask/releases/latest)的 `.dmg` 文件，打开后将 KeyClu 应用移动到“应用程序”文件夹。

## 权限
* 需要 `Accessibility API`（辅助功能）访问权限才能正常运行。
* 建议允许访问 `Notification Center`（通知中心），用于提供不打扰的更新提醒。

## 基本用法
* 连续按两次 `⌘` 键并按住（默认方式），显示当前应用的快捷键
* 按住 `⌘` 键（可选方式），显示当前应用的快捷键

## 功能
KeyClu 支持的部分功能包括：
* 按自己的偏好调整视图
* 将外观个性化设置为 `system`、`light` 或 `dark`
* 收藏快捷键
* 隐藏已知快捷键
* 折叠快捷键分组
* 将应用快捷键导出为 markdown 文件
* 显示 macOS 热键
* 显示 skhd 热键
* 显示自定义快捷键

## 集成
* [CustomShortcuts](https://www.houdah.com/customShortcuts/)：用于自定义快捷键
* [skhd](https://github.com/koekeishiya/skhd)：用于列出快捷键，更多信息请查看 [skhd wiki 页面](https://github.com/Anze/KeyCluCask/wiki/Integrations-%E2%80%90-skhd)
* CLI 参数：更多信息请查看 [CLI 参数 wiki 页面](https://github.com/Anze/KeyCluCask/wiki/Integrations-%E2%80%90-CLI-params)

## 常见问题
### 如果图标被隐藏了，如何打开设置？
只需再次启动应用即可打开设置。

### 应用刚刚崩溃了！
如果遇到崩溃，请提交 issue，并提供详细信息、相关日志，以及崩溃前操作的简短描述。关于如何收集 issue 所需信息，请参考 [FAQ - KeyClu just crashed](https://github.com/Anze/KeyCluCask/wiki/FAQ#keyclu-just-crashed) 页面。你的配合将有助于更高效地解决问题。

## 路线图
可以查看 [KeyClu 的项目看板](https://github.com/users/Anze/projects/1)，了解正在酝酿中的内容！

欢迎随时提出功能请求。

## 隐私政策
KeyClu 不收集任何个人信息，也不使用分析、广告等服务。

## 许可证与致谢
KeyClu 基于 BSD-3-Clause-Clear 许可证发布。详情请查看 [LICENSE](LICENSE)。

本软件使用了以下开源包：
* [Sparkle](https://github.com/sparkle-project/Sparkle)
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift)
* [SQLiteMigrationManager.swift](https://github.com/garriguv/SQLiteMigrationManager.swift)
* [JSON.swift](https://github.com/mikezs/Tisander)

## 翻译
感谢为本项目翻译做出贡献的贡献者：
* zh-CN: [@InTheManXG](https://github.com/InTheManXG)


## 感谢
* 特别感谢所有帮助 KeyClu 发展到当前状态的贡献者
* 感谢 [@wanwindwalker](https://github.com/wanwindwalker) 提供旧版应用图标

## 支持
如果你 ❤️ KeyClu，并且觉得它对你的工作有帮助，欢迎给它 ⭐，也可以请我喝杯咖啡。
