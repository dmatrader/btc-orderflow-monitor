# BTC订单流监控工具 / BTC Order Flow Monitor

> 职业日内交易员专用订单流监控工具演示版 | Professional day trader order flow monitoring tool demo

## 📋 项目说明 / Project Description

**演示版本**: 本工具为作者独立设计的专业交易工具演示版，完整功能属于作者专有软件的一部分  
**Demo Version**: This tool is a demo version of the author's independently designed professional trading tool, full functionality is part of the author's proprietary software

## 📖 项目介绍 / Project Description

**中文**: 这是一个专为职业日内交易员设计的BTC订单流监控工具演示版，支持币安和OKX两大交易所的实时订单流数据监控。工具提供专业级的数据优化呈现，包括实时买卖压力分析、订单流统计、价格深度监控等功能，帮助交易员做出更精准的交易决策。

**English**: This is a demo version of a BTC order flow monitoring tool designed specifically for professional day traders, supporting real-time order flow data monitoring from Binance and OKX exchanges. The tool provides professional-grade data optimization presentation, including real-time buy/sell pressure analysis, order flow statistics, and price depth monitoring to help traders make more precise trading decisions.

## 🚀 快速体验 / Quick Experience

**[在线演示 / Live Demo](https://dmatrader.github.io/btc-orderflow-monitor/)**

**本地运行**: 直接用浏览器打开 `index.html` 文件即可体验演示功能

## ✨ 功能特性 / Features

- 📊 **实时订单流监控** - 监控币安和OKX的BTCUSDT订单流数据
- 🔥 **买卖压力分析** - 实时分析买卖双方压力对比
- 📈 **价格深度监控** - 显示实时价格深度和流动性
- ⚡ **数据优化呈现** - 专业级的数据可视化和统计
- 🎯 **双交易所支持** - 同时监控币安和OKX交易所
- 📱 **响应式设计** - 适配不同屏幕尺寸

## 📖 使用说明 / Usage

### 快速开始

**方法1：在线体验**
- 直接访问：[在线演示](https://dmatrader.github.io/btc-orderflow-monitor/)

**方法2：本地运行**
```bash
# 1. 下载项目文件
git clone https://github.com/dmatrader/btc-orderflow-monitor.git
cd btc-orderflow-monitor

# 2. 用浏览器打开 index.html
# 或者使用本地服务器
python -m http.server 8000
# 然后访问 http://localhost:8000
```

### 功能说明
- **实时数据**: 页面会自动获取和显示实时订单流数据
- **数据统计**: 查看买卖压力、订单流统计等信息
- **多窗口监控**: 支持不同时间窗口的数据监控

## 🎨 界面说明 / Interface Guide

- **币安合约面板**: 显示币安交易所的BTCUSDT订单流数据
- **OKX合约面板**: 显示OKX交易所的BTCUSDT订单流数据
- **订单流监控**: 实时显示买卖订单流统计
- **时间窗口**: 支持不同时间窗口的数据分析

## 🛠️ 技术栈 / Tech Stack

- **HTML5** - 页面结构
- **CSS3** - 样式和布局
- **JavaScript** - 数据处理和交互
- **WebSocket** - 实时数据连接
- **Canvas** - 数据可视化

## 📊 数据来源 / Data Source

- **币安合约**: WebSocket实时订单流数据
- **OKX合约**: WebSocket实时订单流数据
- **数据格式**: 买卖订单、价格、数量、时间戳
- **更新频率**: 实时推送

## 🔗 相关链接 / Related Links

- [币安注册邀请](https://www.binance.com/join?ref=MAPAMBQ1) - 手续费永久返还
- [币安合约官网](https://www.binance.com/zh-CN/futures)
- [OKX合约官网](https://www.okx.com/zh-hans/trade-futures/btc-usdt-swap)

## 📸 预览 / Preview

![BTC订单流监控界面](https://github.com/dmatrader/btc-orderflow-monitor/blob/master/screenshot.png)

## 📁 项目结构 / Project Structure

```
git-btc-orderflow-monitor/
├── index.html              # 主页面文件
├── README.md               # 项目说明文档
└── screenshot.png          # 项目截图
```

## 🚀 快速开始 / Quick Start

1. **克隆项目**
```bash
git clone https://github.com/dmatrader/btc-orderflow-monitor.git
cd btc-orderflow-monitor
```

2. **运行演示**
```bash
# 方法1：直接打开
open index.html

# 方法2：使用本地服务器
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## ⚠️ 免责声明 / Disclaimer

- 本工具仅用于技术演示和学习目的
- 不构成任何投资建议
- 交易有风险，投资需谨慎
- 作者不对使用本工具造成的任何损失负责

## 📄 许可证 / License

**Creative Commons Attribution-NonCommercial 4.0 International License**

- ✅ **允许使用** - 可以查看、下载、修改代码
- ✅ **允许分发** - 可以分享给其他人
- ❌ **禁止商用** - 不能用于商业用途
- 📋 **要求署名** - 使用时需要注明原作者

**CC BY-NC 4.0** - 允许个人使用，禁止商业用途 | Personal use allowed, commercial use prohibited

---

⭐ **如果觉得这个项目有帮助，请给个星标！**  
⭐ **If you find this project helpful, please give it a star!**
