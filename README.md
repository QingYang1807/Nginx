# 交互式 Nginx 手册 (Interactive Nginx Manual)

[![在线演示](https://img.shields.io/badge/Live%20Demo-nginx.qingyang.ai-brightgreen?style=for-the-badge&logo=nginx)](https://nginx.qingyang.ai/)
[![状态](https://img.shields.io/badge/Status-Active-blue?style=for-the-badge)](https://nginx.qingyang.ai/)

这是一个交互式的单页应用（SPA），旨在让 Nginx 的学习过程更直观、更富趣味性。它将官方的静态文档转化为一个可视化的、可动手操作的学习平台，帮助用户从入门到精通，深入理解 Nginx 的底层原理和高级用法。

## 核心功能

- **🚀 引导式学习路径**: 内容组织从入门简介、工作模型，到核心配置、高级主题和故障排查，结构清晰，循序渐进。
- **⚙️ 交互式图解**: 动态展示 Nginx 的配置文件层级结构，点击即可查看各模块的核心指令与说明。
- **⚖️ 实时模拟**: 通过动态图表演示负载均衡的三种核心算法（轮询、最少连接、IP 哈希），将抽象概念可视化。
- **⚡️ 性能计算器**: 实时计算 `worker_processes` 和 `worker_connections` 对理论最大连接数的影响。
- **📦 一站式安装指南**: 使用标签页聚合了 Ubuntu, CentOS, Docker, WSL 等主流平台的安装步骤。
- **📋 代码一键复制**: 所有配置示例均提供“复制”按钮，方便用户在实际环境中快速应用。
- **🩺 常见错误排查**: 系统性地梳理了 502, 504, 413 等常见错误的原因及解决方案，实用性强。

## 在线演示

您可以直接访问以下地址开始学习：

**[https://nginx.qingyang.ai/](https://nginx.qingyang.ai/)**

## 技术栈

本项目完全基于前端技术构建，无后端依赖。

-   **HTML5**
-   **Tailwind CSS**: 用于快速构建现代化、响应式的界面。
-   **Vanilla JavaScript**: 负责实现所有的交互逻辑、页面导航和动态内容更新。
-   **Chart.js**: 用于创建负载均衡算法的动态模拟图表。

## 如何使用

无需任何安装，直接在浏览器中访问 [nginx.qingyang.ai](https://nginx.qingyang.ai/) 即可。

## 如何贡献

如果您对内容有任何改进建议（例如补充新的知识点、修正错误）或发现了任何 Bug，欢迎通过提 Issue 的方式进行反馈。

## 开源协议

本项目采用 [MIT](https://opensource.org/licenses/MIT) 协议。

---

# Interactive Nginx Manual

[![Live Demo](https://img.shields.io/badge/Live%20Demo-nginx.qingyang.ai-brightgreen?style=for-the-badge&logo=nginx)](https://nginx.qingyang.ai/)
[![Status](https://img.shields.io/badge/Status-Active-blue?style=for-the-badge)](https://nginx.qingyang.ai/)

This is an interactive single-page application (SPA) designed to make learning Nginx more intuitive and engaging. It transforms the official static documentation into a visual, hands-on learning platform, helping users progress from beginner to expert by deeply understanding Nginx's underlying principles and advanced usage.

## Key Features

- **🚀 Guided Learning Path**: Content is clearly structured from introduction and worker model to core configuration, advanced topics, and troubleshooting.
- **⚙️ Interactive Diagrams**: Dynamically visualizes the Nginx configuration file structure. Users can click on different blocks to see key directives and their explanations.
- **⚖️ Live Simulations**: Demonstrates the three core load-balancing algorithms (Round Robin, Least Connections, IP Hash) with a dynamic chart, making abstract concepts easy to grasp.
- **⚡️ Performance Calculator**: Instantly calculates the theoretical maximum client connections based on `worker_processes` and `worker_connections`.
- **📦 All-in-One Installation Guide**: Uses tabs to consolidate installation steps for major platforms like Ubuntu, CentOS, Docker, and WSL.
- **📋 One-Click Code Copy**: All configuration examples come with a "Copy" button for easy application in real-world scenarios.
- **🩺 Troubleshooting Guide**: Systematically breaks down common errors like 502, 504, and 413, providing causes and practical solutions.

## Live Demo

You can start learning right away by visiting:

**[https://nginx.qingyang.ai/](https://nginx.qingyang.ai/)**

## Technology Stack

This project is built entirely with front-end technologies and has no backend dependencies.

-   **HTML5**
-   **Tailwind CSS**: For building a modern, responsive user interface.
-   **Vanilla JavaScript**: Powers all interactive logic, page navigation, and dynamic content updates.
-   **Chart.js**: Used for creating the dynamic visualizations for the load balancing simulator.

## How to Use

No installation is required. Simply visit [nginx.qingyang.ai](https://nginx.qingyang.ai/) in your browser to get started.

## How to Contribute

Suggestions for content improvements (such as adding new topics or correcting errors) and bug reports are welcome. Please feel free to open an issue.

## License

This project is distributed under the [MIT](https://opensource.org/licenses/MIT) License.