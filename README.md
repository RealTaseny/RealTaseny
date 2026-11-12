<h1 align="center">你好，我是 Taseny 👋</h1>

<p align="center"><strong>嵌入式开发 · C/C++ · 开发工具</strong></p>
<p align="center"><em>Per aspera ad astra.</em></p>

---

我喜欢做软硬件交界处的项目，从 STM32 智能车的驱动和调试，到在桌面上模拟 OLED 菜单。这里也放了一些能单独拿去用的 C++ 组件，比如用来在线程间传递最新数据的三缓冲。

## 最近在做什么

- **机器人感知与点云配准** · 我在关注 ROS 2 / SLAM 里的点云配准，也给 KISS-Matcher 提交了一个修复，处理离群点剔除阶段的 ROBIN 图内存泄漏。[KISS-Matcher PR #110](https://github.com/MIT-SPARK/KISS-Matcher/pull/110)
- **AI 辅助理解代码** · 我在探索如何用大模型生成代码架构图，帮助理解陌生的代码库。最近在自己的 CodeBoarding 分支里给 CLI 加入了 DeepSeek 思考模式和 SOCKS 代理支持。[CodeBoarding 提交](https://github.com/RealTaseny/CodeBoarding/commit/9ea4539d6f3ab2c35df59c3da3130a7eb2db93d0)

## 代表项目

- **[Easy Menu Builder](https://github.com/RealTaseny/Easy_Menu_builder)** · 用 Qt 6 搭建和预览嵌入式 OLED 菜单，支持生成 C++ 代码和热重载仿真。
- **[Smart Car Template](https://github.com/RealTaseny/Smart_Car_Template)** · 基于 STM32F411 的智能车工程模板，包含无刷电机、舵机和传感器驱动，以及 YMODEM 通信。
- **[triple_buffer](https://github.com/RealTaseny/triple_buffer)** · 只需包含头文件的 C++11 无锁三缓冲，用于单生产者、单消费者之间传递最新数据。

## 🧱 Breakout 贡献图

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RealTaseny/RealTaseny/output/breakout-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RealTaseny/RealTaseny/output/breakout-contribution-graph.svg">
  <img alt="Breakout contribution graph" src="https://raw.githubusercontent.com/RealTaseny/RealTaseny/output/breakout-contribution-graph.svg">
</picture>
