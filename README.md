# Doxygen Previewer

Show the preview of Doxygen documentation for the file being written.  
（今まさに編集しているファイルのdoxygenを生成し表示します。）

## Target & Environment (Requirements)

* for the file having extension c, h, cpp, hpp. <br>（c, h, cpp, hppのファイルを処理します。それ以外は無視します。）
* for Windows (x64) <br>（Windows環境 x64を想定しています。）
    + Need TMP environment variable in your system <br>（TMP環境変数が設定されていることが必要です。）

## Usage

* Please enter `doxygen preview` while focusing on source code.  
  （ソースコード（cやh）をアクティブにした状態で、`doxygen previewer`コマンドを(ctrl+shift+pから)実行してください。）
    + You can move the links. (リンクを移動できます)
    + If you want to back to the previous page, press `ctrl + Left`. （ctrl+左矢印で前の画面に戻れます）

### Trouble Shooting

* If you find the message `Please close %Temp% directory`, please enter the command again.  
  （実行時にもし`Please close %Temp% directory`と出た場合は再度コマンドを実行してみてください。）

## more information

* [Github repository](https://github.com/hakua-doublemoon/DoxygenPreviewer)

* [Introduction in Qiita](https://qiita.com/hakua-doublemoon/items/c328a7bf0bc7a1fbef14)

* [Doxygen](https://github.com/doxygen/doxygen)
    * 内部のdoxygen生成機能はdoxygenのaddon/doxyappの改造品を使っています。それらDoxygenに直接由来するバイナリーやソースコードのライセンスはDoxygenのライセンスに依存します。



---

## 简体中文说明

本项目基于 hakua-doublemoon 开发的 DoxygenPreviewer，计划增加简体中文和日文支持。

### 开发目标

- 提供简体中文和日文使用说明。
- 支持根据 VS Code 显示语言自动切换。
- 为插件的操作提示增加中文翻译。
- 保留原作者的版权声明和许可证。

### 原始项目

https://github.com/hakua-doublemoon/DoxygenPreviewer

**当前状态：** 多语言支持开发准备阶段。
