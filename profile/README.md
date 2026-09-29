<p align="center">
  <img src="qingjian-mark.png" alt="青简竹简图标" width="72">
</p>

<h1 align="center">青简 Qingjian</h1>

<p align="center"><strong>好好输入，顺便多认识一个词。</strong></p>

<p align="center">
  <a href="https://qingjian.app">官网</a> ·
  <a href="https://qingjian.app/download">下载</a> ·
  <a href="https://qingjian.app/docs">使用文档</a> ·
  <a href="https://github.com/qingjian-team/qingjian/issues/new/choose">反馈</a>
</p>

青简是一款输入法。像平常一样输入拼音、选择候选、写完整句；候选旁的一条译词，让语言学习自然发生在日常输入里。译词是辅助信息，输入始终是主体。

```text
1  开发        development
2  编程        programming
3  架构        architecture
```

学习语言可选英语、日语或西班牙语，一次只显示一种，也可以关闭译词。整句输入、简拼、拼写纠错、双拼、五笔和本地整句模型，都是为了先把字打好。

## 下载与使用

- **macOS、Windows**：已有可下载安装的测试版；从[下载页](https://qingjian.app/download)选择安装包，按[安装说明](https://qingjian.app/docs/getting-started/install)开始使用。
- **Linux**：已有 Fcitx5 版本，使用系统默认候选面板，目前需要手动启动后台服务。见 [Linux 使用说明](https://qingjian.app/docs/getting-started/linux)。

按键、设置、译词与数据位置都在[使用文档](https://qingjian.app/docs)。

## 数据与隐私

拼音转换、词库查询、本地模型、输入习惯学习和输入量统计都在设备上完成；青简不需要账号，也不上传本地统计。输入日志只保存在本机，可在设置中关闭或清空。检查更新会向官网请求版本列表，也可以关闭。

可选的云联想默认关闭。开启后，青简会将当前输入及附近文字直接发送给用户自行填写的 AI 服务商，请求不经过青简的服务器。详见[数据与日志](https://qingjian.app/docs/help/data-and-logs)。

## 项目仓库

| 仓库 | 内容 |
|---|---|
| [`qingjian`](https://github.com/qingjian-team/qingjian) | 输入法源码、用户文档与开发文档；代码采用 GPL-3.0-or-later 许可 |
| [`qingjian-web`](https://github.com/qingjian-team/qingjian-web) | [qingjian.app](https://qingjian.app) 官网源码 |
| [`.github`](https://github.com/qingjian-team/.github) | 当前组织主页 |

---

<details>
<summary>English</summary>

Qingjian is an input method that puts a small translation beside each candidate while you type. Choose English, Japanese, or Spanish as your learning language, or turn translations off. Sentence conversion, typo correction, shuangpin, Wubi, and a local sentence model support everyday typing.

Test builds are available for macOS and Windows. A Linux Fcitx5 version is also available; it currently uses the default candidate panel and requires the background service to be started manually. [Download Qingjian](https://qingjian.app/download) or read the [user guide](https://qingjian.app/docs).

Local conversion and usage statistics stay on your device. There is no account or telemetry upload. Optional cloud suggestions are off by default; when enabled, your current input and nearby text go directly to the AI provider you configure. The source code is available in [`qingjian`](https://github.com/qingjian-team/qingjian) under GPL-3.0-or-later.

</details>
