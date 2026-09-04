[English](readme.md) | [简体中文](readme.zh-CN.md) | 日本語

<p align="center">
  <img src="https://github.com/Anze/KeyCluCask/blob/main/img/keyclu.png?raw=true" height="128" />
  <h1 align="center">KeyClu for macOS</h1>
</p>

アプリのショートカットなどを簡単に一覧表示できます。使い方は簡単: `⌘` キーを2回押してそのまま押し続けるだけで一覧表示を見られます。

![platform:macos  + Intel](https://img.shields.io/badge/platform-macOS__+_Intel-2F3640.svg)
![version:bigsur](https://img.shields.io/badge/requirements-Big_Sur%2B-337AFF.svg)
![category:productivity](https://img.shields.io/badge/category-productivity-blue.svg)
![license:bsd-3-clause-clear](https://img.shields.io/badge/license-BSD--3--Clause--Clear-orange.svg)

[![github downloads](https://sergii.tatarenkov.name/apps/keyclu/github-downloads.svg)](https://github.com/Anze/KeyCluCask/releases/latest)
[![brew installs](https://sergii.tatarenkov.name/apps/keyclu/brew-downloads.svg)](https://formulae.brew.sh/cask/keyclu)
[![crowdin](https://badges.crowdin.net/keyclu/localized.svg)](https://crowdin.com/project/keyclu)
[![keyclu website](https://img.shields.io/badge/website-KeyClu-337AFF)](https://sergii.tatarenkov.name/apps/keyclu/)

## スクリーンショット
![screenshot1](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_1.png)

![screenshot2](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_2.png)

![screenshot3](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_3.png)

![screenshot4](https://raw.githubusercontent.com/Anze/KeyCluCask/main/img/screenshot_4.png)

## インストール方法
### Homebrew
Homebrew を使ってインストールするには、ターミナルを開いて次のように入力します：
```
brew install --cask keyclu
```
### 手動インストール
まず [最新版](https://github.com/Anze/KeyCluCask/releases/latest) `.dmg` をダウンロードします。次にそのファイルを開いて KeyClu アプリをアプリケーションフォルダに移動させてください。

## 権限
* 操作するには `アクセシビリティ API` へのアクセスが必要です。
* `通知センター` へのアクセスは、優しい更新通知のために推奨されます。

## 基本的な使い方
* `⌘` キーを 2 回押し、2 回目を押したままにすると、現在のアプリのショートカットを表示します (標準の操作)。
* `⌘` キーを 1 回押したままにして、現在のアプリのショートカットを表示することもできます。

## 機能
* 好みに合わせて表示を調整
* 外観を `システム`、`ライト` そして `ダーク`に変更
* ショートカットをブックマーク
* 分かっているショートカットを非表示
* ショートカットのグループ （メニュー） を折りたたむ
* アプリのショートカットをマークダウン形式のファイルに書き出し
* macOS ホットキーを表示
* macOS ジェスチャを表示
* skhd ホットキーを表示
* Jitouch2 ジェスチャを表示
* 自分で定義したショートカットを表示

## サードパーティ製アプリとの連携
* [CustomShortcuts](https://www.houdah.com/customShortcuts/) ショートカットをカスタマイズできます。
* [skhd](https://github.com/koekeishiya/skhd) でショートカットを一覧表示できます。詳細は [skhd Wiki](https://github.com/Anze/KeyCluCask/wiki/Integrations-%E2%80%90-skhd) をご覧ください。
* CLI パラメータによる連携。詳細は [CLI params Wiki](https://github.com/Anze/KeyCluCask/wiki/Integrations-%E2%80%90-CLI-params) をご覧ください。

## よくある質問と解答
### アイコンが非表示の場合、設定を開くにはどうすればよいですか？
設定画面を開くには、アプリを再度起動してください。

### アプリがクラッシュしてしまいました！
クラッシュが発生した場合は、Issue ページを開き、詳細や関連するログ、クラッシュにつながった可能性のある操作について簡単にお知らせください。問題に必要な情報を収集するためのガイダンスとして、よくある質問のページ [FAQ - KeyClu just crashed](https://github.com/Anze/KeyCluCask/wiki/FAQ#keyclu-just-crashed) をご確認ください。ご協力いただけると、より効果的に問題を解決できるようになります。

## ロードマップ
[KeyClu のプロジェクトボード](https://github.com/users/Anze/projects/1)で、現在進行中の項目をご確認いただけます。

機能リクエストはいつでも大歓迎です。

## プライバシー方針
KeyClu は個人情報を収集せず、分析や広告などを目的としたサービスも使用しません。

## ライセンスとクレジット
KeyClu は BSD-3-Clause-Clear ライセンスの下でリリースされています。詳細は [ライセンス](LICENSE) をご覧ください。

このソフトウェアは以下のオープンソースパッケージを使用しています：
* [Sparkle](https://github.com/sparkle-project/Sparkle)
* [SQLite.swift](https://github.com/stephencelis/SQLite.swift)
* [SQLiteMigrationManager.swift](https://github.com/garriguv/SQLiteMigrationManager.swift)
* [JSON.swift](https://github.com/mikezs/Tisander)

## 翻訳
翻訳にご協力いただいた方々に感謝いたします。
* ja-JP: [@9demaio1964](https://github.com/9demaio1964)
* zh-CN: [@InTheManXG](https://github.com/InTheManXG)

## 謝辞
* ご協力いただいた皆様に感謝いたします
* 従来のアプリアイコン [@wanwindwalker](https://github.com/wanwindwalker)

## サポート
もし KeyClu を気に入ってお役に立ったと感じたら、ぜひ⭐を付けて、コーヒーで応援してください。
