# [Chat Simplifier](https://chat-simplifier.vercel.app/)
[![](https://img.shields.io/badge/chat-on%20discord-7289da.svg?sanitize=true)](https://chat.imzbb.cc)

这个项目使用AI为您简化聊天内容。

[![Chat Simplifier](./public/screenshot.png)](https://chat-simplifier.vercel.app/)

## 它是如何工作的？

该项目使用[OpenAI GPT-3 API]和[Vercel Edge函数]进行流式处理。它根据表单和用户输入构造一个提示，通过Vercel Edge函数将其发送到GPT-3API，然后将响应流回到应用程序

## Running Locally

克隆该项目后，去[OpenAI](https://beta.openai.com/account/api-keys)创建帐户并将API密钥放入名为“.env”的文件中。
然后，在命令行中输入以下命令运行应用程序，使用 `http://localhost:3000`打开网页。

```bash
npm run dev
```

## Credits

Inspired by [TwtterBio](https://github.com/Nutlope/twitterbio) and [Jimmy Lv](https://www.bilibili.com/video/BV17M411i7B6).

## 支持

如果你觉得这个工具对您有帮助，可以帮作者买一杯果汁 🍹 表示支持

![](https://imzbb.cc/img/sponsorship.png)
