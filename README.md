# 🛡️ Zero-Trust Protocol Defense Simulator / 零信任金融协议攻防演练模拟器
## 🌐 English Description

### Overview
**Zero-Trust Protocol Defense Simulator** is a lightweight, single-file interactive web application engineered for financial technology, crypto payment gateways, and high-security system architects. It visualizes dynamic security gate blocking, topological pipeline traversal, 0-day vulnerability slip-throughs, and automated remediation workflows under compromised developer terminal / rogue AI credential scenarios.

### 🌟 Key Features
- **Multi-Layer Defense Sandbox**: Toggleable security layers including Hardware Key (MPC Sign), Formal Policy Sandbox, Dynamic Rate Limit Circuit Breaker, and WORM Cryptographic Audit Chain.
- **Attack Vector Simulations**: Built-in scenarios simulating single large unauthorized withdrawals, high-frequency smurf attacks (rate bypass), and audit log tampering.
- **Probabilistic 0-Day Risk Factor**: Adjustable slider modeling unknown vulnerability slip-through probabilities for realistic stress testing.
- **Automated Remediation (Auto-Patch)**: Triggers an automated Post-Mortem Incident Report upon completion with one-click full defense policy restoration.
- **Bilingual Interface**: Native support for real-time Chinese/English UI switching.
- **Zero-Dependency Architecture**: Standalone single-file HTML (React 18 + Tailwind CSS via CDN) requiring no Node.js or local build environment—just double-click to run!

### 🚀 Quick Start
1. Clone or download `index.html` from this repository.
2. Double-click `index.html` to open it in any modern web browser (Chrome, Edge, Safari).

<a name="chinese"></a>
## 🇨🇳 中文说明

### 项目简介
**零信任金融协议攻防演练模拟器** 是一款专为金融科技、加密出金网关与高安全架构师设计的轻量级单文件交互式演练系统。系统在工程师终端失陷、内部 AI 凭证被盗等极限场景下，可视化展示协议层动态拦截、拓扑链路穿透、0-day 漏洞概率绕过以及自动化应急响应闭环。

### 🌟 核心特性
- **多层防御策略沙箱**：集成硬件 MPC 多方签名、形式化验证沙箱、动态流速熔断器及 WORM 防篡改审计链的动态开关。
- **真实攻防向量模拟**：内置大额越权提现、高频“蚂蚁搬家”式刷单、运维日志与审计痕迹擦除等典型场景。
- **0-day 漏洞概率风险模型**：通过动态风险滑块模拟高级黑客利用未知漏洞的概率穿透，支持抗打击极限压力测试。
- **一键自动化修补 (Auto-Remediation)**：演练结束后自动生成安全事故根因报告（Post-Mortem Report），并支持一键满血恢复全部防线。
- **双语一键切换**：支持中英文界面即时无缝切换。
- **零依赖单文件架构**：基于 React 18 与 Tailwind CSS 构建，无需配置复杂的 Node.js 环境或依赖包，双击文件即可运行。

### 🚀 快速开始
1. 下载本仓库中的 `index.html` 文件。
2. 直接在本地双击 `index.html`，使用任意主流浏览器打开即可体验。


## 🛠️ Architecture & Core Concepts / 核心设计原理

| Defense Mechanism / 防御机制 | Technical Concept / 技术原理 | Target Scenario / 应对场景 |

| **Hardware MPC Key** | Disallows non-HSM API automated execution | Unauthorized Large Transfer / 大额越权划转 |
| **Formal Policy Sandbox** | Mathematical invariant checks on AI/API commands | Rogue AI & Prompt Injection / 违规指令 |
| **Dynamic Rate Limiter** | Global net outflux velocity monitoring & freeze | High-Freq Micro-Withdrawal / 蚂蚁搬家刷单 |
| **WORM Audit Chain** | Write Once Read Many cryptographic hash log stream | Evidence Tampering & Wipe / Log 抹除与销毁 |
