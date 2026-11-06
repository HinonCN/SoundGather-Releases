# 拾声 SoundGather

<img width="112" height="112" alt="拾声 SoundGather 图标" src="https://github.com/user-attachments/assets/50142714-dd61-4003-b8da-aaf21d73bdc3" />

让音乐和音效素材更好找、更好用。

拾声是一款面向剪辑师、影视后期与内容创作者的本地音频素材管理工具，支持 macOS 和 Windows。

把硬盘里的音乐与音效导入拾声，即可通过波形快速试听，用素材箱、标签和颜色整理分类，再将需要的素材拖入剪辑软件。遇到一组好用的声音搭配，也可以保存下来，供下次创作直接调用。

[![最新版本](https://img.shields.io/github/v/release/HinonCN/SoundGather-Releases?label=最新版本&color=2ea44f)](https://github.com/HinonCN/SoundGather-Releases/releases/latest)
[![macOS](https://img.shields.io/badge/macOS-13%2B-111111?logo=apple)](https://github.com/HinonCN/SoundGather-Releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011%2064位-0078D4?logo=windows)](https://github.com/HinonCN/SoundGather-Releases/releases/latest)

## 下载安装

0.3.0 正式版提供以下安装包：

| 设备 | 下载 |
| --- | --- |
| Apple 芯片 Mac（M 系列） | [macOS arm64 安装包](https://github.com/HinonCN/SoundGather-Releases/releases/download/v0.3.0/SoundGather-0.3.0-macOS-arm64.dmg) |
| Intel Mac | [macOS x64 安装包](https://github.com/HinonCN/SoundGather-Releases/releases/download/v0.3.0/SoundGather-0.3.0-macOS-x64.dmg) |
| Windows 10 / 11 64 位 | [Windows x64 安装包](https://github.com/HinonCN/SoundGather-Releases/releases/download/v0.3.0/SoundGather-Setup-0.3.0-Windows-x64.exe) |

[最新版本与更新说明](https://github.com/HinonCN/SoundGather-Releases/releases/latest) · [历史版本](https://github.com/HinonCN/SoundGather-Releases/releases) · [0.3.0 文件校验值](https://github.com/HinonCN/SoundGather-Releases/releases/download/v0.3.0/SoundGather-0.3.0-SHA256.txt)

Mac 用户可在“ → 关于本机”查看芯片类型。下载时请选择上表中的安装包，GitHub 自动生成的 Source code 压缩包不是软件安装程序。

## 主要功能

- 波形试听与搜索：导入音频文件或整个文件夹，直接点击波形定位试听；支持按名称、艺人、文件夹和路径搜索，并结合标签、颜色与收藏筛选。搜索历史可设置保留数量或关闭显示。
- 素材库项目与分层整理：为不同工作建立独立素材库，使用多级素材箱收纳音乐与音效。支持拖拽归类、批量添加标签、收藏和颜色标记，项目存储位置可自行指定。
- 选区裁切：在播放位置按 I / O 标记片段，拖动边界精调并试听。将选区拖出时生成独立音频，可选择 WAV、MP3 及相应输出规格；仅创建选区不会生成文件。
- 搭配收藏：把经常一起使用的音乐、转场声和情绪音效存成一组，支持排序与备注。下次可快速找回并整组拖出，各个音频仍保留为独立文件。
- 修剪合成：在底部时间线调整音频的排列、首尾、音量与淡入淡出，试听后保存合成方案，或输出一条 WAV、MP3 音频。
- NCM 音频转换：在本地批量处理 NCM 文件，可保留内部 MP3、FLAC 格式，或转换为 WAV、MP3。结果可导出到指定文件夹，也可直接存入素材库项目。
- 素材库工程交接：按素材箱的父子层级复制音频到新位置，并生成 .sgproject 工程文件。将整个文件夹交给另一台电脑后，可通过导入工程恢复素材箱结构与整理信息。
- 纯净模式与个性化：将素材窗口置顶，与剪辑软件同屏使用；可调整列数、波形高度、主题和背景，快捷键支持键盘及鼠标按键。设置中也可查看和清理缓存空间。

## 一个常用工作流

1. 导入素材文件夹，为当前项目建立素材箱。
2. 搜索并点击波形试听，找到需要的音乐或音效。
3. 需要整条音频时直接拖出；只需要其中一段时，用 I / O 创建选区再拖出。
4. 遇到好用的音效搭配，多选后存入“搭配收藏”，下次直接复用。

素材箱和搭配收藏保存的是整理关系，不会移动源音频。选区裁切、修剪合成和格式转换会另存输出文件，不修改原始音频。

## 界面预览

纯净模式适合与剪辑软件同屏浏览素材，集中显示素材箱、搜索、筛选和波形。

![拾声纯净模式](assets/screenshots/soundgather-pure-mode.png)

内置多套主题，支持自定义强调色、背景与界面密度。

![拾声外观设置](assets/screenshots/soundgather-appearance.png)

## 安装与更新

macOS 需要 13.0 或更高版本。打开 DMG 后，将“拾声”拖入“应用程序”。当前安装包采用本地签名，尚未经过 Apple Developer ID 公证；如系统拦截，可在“系统设置 → 隐私与安全性”中确认打开。

Windows 安装包适用于 Windows 10 / 11 64 位，可在安装向导中选择安装位置。当前未配置发布者数字签名，若出现 SmartScreen 提示，请先确认文件来自本仓库。

软件联网后可检查 GitHub 新版本，支持识别正式版与测试版，在软件内查看更新说明并下载安装包。安装由用户确认，不会静默覆盖当前版本。

## 数据与反馈

音频索引、素材箱、标签、收藏、波形缓存与运行日志均保存在本机。素材浏览、整理和 NCM 转换在本地完成，不会将音频上传到服务器。源文件移动或断开连接后，可通过重新链接恢复使用。

遇到导入、播放或运行问题，可在设置的“关于”页面导出诊断日志，附上软件版本、操作步骤和问题截图，方便定位。

[提交问题或建议](https://github.com/HinonCN/SoundGather-Releases/issues) · 邮箱：[cn_teaplant@163.com](mailto:cn_teaplant@163.com)

[小红书](https://xhslink.cn/m/2XXBZPPLEbn) · [哔哩哔哩](https://b23.tv/uWvp1eB) · [抖音](https://v.douyin.com/lSMizv-hUoc/)

作者：Hinon沐光。开发鸣谢：@买敌敌畏送吸管。

本仓库用于拾声的官方版本发布、安装包下载和更新信息，不包含应用源代码。
