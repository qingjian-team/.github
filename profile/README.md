<p align="center">
  <img src="qingjian-mark.png" alt="青简" width="52">
</p>

<h1 align="center">青简 Qingjian</h1>

<p align="center">输入的不只是文字。</p>

<p align="center">
  <a href="https://qingjian.app">官网</a> ·
  <a href="https://qingjian.app/docs">文档</a> ·
  <a href="https://qingjian.app/download">下载</a>
</p>

---

青简是一个用 Rust 写的拼音输入法。它的目标不只是「把拼音变成汉字」，
而是让输入本身成为一种轻量、持续、几乎没有额外负担的语言接触方式。

打字时，候选词旁边多一条你正在学的那门语言的译词：

```text
1  开发            v. develop
2  编程            v. program
3  架构            n. architecture
4  编译            v. compile
5  语言            n. language
```

候选词仍然是主体，译词只是较小、较浅的辅助信息。把学习语言换成日语，开发 · 学习 · 语言 会显示「開発(かいはつ)する · 勉強(べんきょう)する · 言語(げんご)」。
见得还不多的译词画成橙色，看熟了自动变回灰色。

## 三条原则

- **先是一个好用的输入法。** 整句转换、拼写纠错、模糊音、双拼、中英混输、emoji，输入效率不为学习让路。
- **一次只学一种语言。** 一个候选只显示一条译词，不在候选框里同时塞进英语、日语、韩语、德语。
- **不打断。** 不弹题，不强迫记忆，只是把译词悄悄放在那里。如果用户需要思考「我现在是在打字还是在背单词」，那就是设计错了。

## 仓库

| 仓库 | 内容 |
|---|---|
| [`qingjian`](https://github.com/qingjian-team/qingjian) | 输入法本体：平台无关的核心引擎、macOS 输入法、数据生成工具、设计文档与用户文档 |
| `qingjian-web` | 官网 [qingjian.app](https://qingjian.app) 的源码，「文档」页从主仓库拉取 |
| `.github` | 这个页面 |

## 平台

核心引擎平台无关，各平台只负责接入系统输入接口与候选窗口。

```text
macOS    → Input Method Kit (IMK)     已可用（测试版）
Windows  → Text Services Framework   计划中
Linux    → IBus / Fcitx              计划中
```

## 隐私

青简没有自己的服务器，不上传任何数据。拼音转换、词库、学习、释义全部在本机完成，没有账号，没有统计上报。
可选的云联想缺省关闭，打开后数据直接从你的电脑发到你自己填写的 AI 服务商，密码框里绝不发送。

## 状态

测试版，作者自用中，正在给少数测试者打包。安装包、文档与更新日志都在 [qingjian.app](https://qingjian.app)。
源码以 GPL-3.0-or-later 开源，在 [qingjian-team/qingjian](https://github.com/qingjian-team/qingjian)。

---

<details>
<summary>English</summary>

Qingjian (青简, "green bamboo slips") is a Chinese pinyin input method written in Rust.
Next to each candidate it shows one translation in the language you are learning, English or Japanese, one at a time.
Translations you have not seen much yet are drawn in orange and fade back to grey as they become familiar.

It is an input method first: sentence conversion, typo correction, fuzzy pinyin, shuangpin, mixed English input and emoji all come before the learning feature, which never interrupts typing.

Everything runs on your machine. There are no accounts and no telemetry. The optional cloud suggestions are off by default and, when enabled, talk only to the AI provider you configure yourself.

macOS is available as a beta; Windows and Linux are planned. The source is on GitHub under GPL-3.0-or-later.

</details>
