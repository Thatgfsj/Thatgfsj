<a name="readme-top"></a>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Thatgfsj/Thatgfsj/main/assets/header-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Thatgfsj/Thatgfsj/main/assets/header-light.svg">
    <img alt="Thatgfsj — 代码为主，语言跟着问题走" src="https://raw.githubusercontent.com/Thatgfsj/Thatgfsj/main/assets/header-light.svg" width="100%">
  </picture>
</p>

<h1 align="center">Thatgfsj</h1>

<p align="center">
  写代码为主，语言跟着问题走：Python、Rust、C++、Kotlin、TypeScript 按需取用。
</p>

<p align="center">
  <a href="https://www.thatgfsj.xyz/"><img alt="博客 thatgfsj.xyz" src="https://img.shields.io/badge/%E5%8D%9A%E5%AE%A2-thatgfsj.xyz-667eea?style=flat-square&logo=rss&logoColor=white"></a>
  <a href="mailto:thatgfsj2324@gmail.com"><img alt="邮箱 thatgfsj2324@gmail.com" src="https://img.shields.io/badge/Email-thatgfsj2324-764ba2?style=flat-square&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/Thatgfsj?tab=repositories"><img alt="公开仓库数" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FThatgfsj&query=%24.public_repos&label=%E5%85%AC%E5%BC%80%E4%BB%93%E5%BA%93&style=flat-square&color=667eea"></a>
  <a href="https://github.com/Thatgfsj"><img alt="关注者数" src="https://img.shields.io/github/followers/Thatgfsj?label=%E5%85%B3%E6%B3%A8%E8%80%85&style=flat-square&color=764ba2"></a>
</p>

<p align="center">
  <a href="#关于">关于</a> ·
  <a href="#仓库">仓库</a> ·
  <a href="#文章">文章</a> ·
  <a href="#数据">数据</a>
</p>

---

## 关于

我是 Thatgfsj。写代码为主，语言跟着问题走：Python、Rust、C++、Kotlin、TypeScript 都用，按需取用。仓库里大多是自己要用的东西，于是有了这些项目。过程中值得记录的部分，整理成了[博客文章](https://www.thatgfsj.xyz/)。

在做的事：

- **Android / Kotlin** —— Jetpack Compose 应用（[MyPackage](https://github.com/Thatgfsj/MyPackage)）、[中国象棋引擎](https://github.com/Thatgfsj/xiangqi)、[Android TV 直播客户端](https://github.com/Thatgfsj/TVLive)
- **Rust / 系统工具** —— [语音输入](https://github.com/Thatgfsj/voiceinput)、[校园网保活](https://github.com/Thatgfsj/XXGCXY-CampusNet-AutoLogin)、多 Agent 工作流 [Flowntier](https://github.com/Thatgfsj/Flowntier)
- **网络协议** —— 路由器私有协议逆向、强制门户（Portal）认证机制
- **AI Agent 工具链** —— [DSH 插件与技能](https://github.com/Thatgfsj/dsh-plugin-skills)、多智能体记忆系统 [neuroweave-cortex](https://github.com/Thatgfsj/neuroweave-cortex)、[README 表头设计技能](https://github.com/Thatgfsj/readme-header-design)

## 仓库

<table>
  <tr><th>项目</th><th>说明</th></tr>
  <tr><td><a href="https://github.com/Thatgfsj/neuroweave-timeline">neuroweave-timeline</a></td><td>记录项目演进过程的 process memory</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/Flowntier">Flowntier</a></td><td>多 Agent 协作工作流的实验项目</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/claude-email-cli">claude-email-cli</a></td><td>用邮件控制 Claude 的命令行工具</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/voiceinput">voiceinput</a></td><td>Rust 写的语音输入工具</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/XXGCXY-CampusNet-AutoLogin">XXGCXY-CampusNet-AutoLogin</a></td><td>校园网自动登录与保活</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/ai-website-detector">ai-website-detector</a></td><td>检测网页是否由 AI 工具生成</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/TVLive">TVLive</a></td><td>Android TV 直播客户端</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/xiangqi">xiangqi</a></td><td>中国象棋 Android 版，alpha-beta 迭代加深引擎</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/tarot-oracle">tarot-oracle</a></td><td>单屏塔罗抽牌应用，78 张牌全离线</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/MyPackage">MyPackage</a></td><td>快递驿站管理 Android 应用，Jetpack Compose</td></tr>
  <tr><td><a href="https://github.com/Thatgfsj/android-gradle-skills">android-gradle-skills</a></td><td>Android/Gradle 构建体系的 agent skill</td></tr>
</table>

## 文章

写得不多，重在过程完整：抓包、协议分析、工程实现、踩坑，一条主线。

- [用 C++ 写一个 ZTE 路由器实时网速监控小工具](https://www.thatgfsj.xyz/blog/2026/07/router-monitor/)——从浏览器抓包逆向 ZTE 路由器私有协议，到纯 Win32 单文件程序
- [校园网 Web 认证（Portal Authentication）机制详解](https://www.thatgfsj.xyz/blog/2026/06/campus-network-portal-authentication/)——强制门户的检测逻辑、登录加密字段与组网形态

## 数据

<div align="center">
  <img src="https://ghchart.rshah.org/667eea/Thatgfsj" alt="Thatgfsj 的 GitHub 贡献图" width="800" />
</div>

---

<p align="center">
  <sub>表头用 <a href="https://github.com/Thatgfsj/readme-header-design">readme-header-design</a> 生成：横幅是仓库内的自绘 SVG，随主题自动切换明暗两版。</sub>
</p>

<p align="center"><a href="#readme-top">↑ 回到顶部</a></p>
