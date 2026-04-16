# 家里有什么 🏠

> 拍照录入、自然语言搜索、再不用翻箱倒柜

一个简洁优雅的家庭物品管理 Web 应用，帮助你轻松管理家里的每一样东西。

![Preview](https://img.shields.io/badge/Preview-Live%20Demo-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## ✨ 功能特点

- 📷 **拍照录入** — 拍张照片，标记位置，快速保存
- 🔍 **全文搜索** — 搜一下"护照"，立刻知道在哪
- 🏠 **房间分类** — 按房间浏览，找东西更方便
- 🏷️ **标签管理** — 证件、工具、药品...分类清晰
- 📱 **响应式设计** — 手机、平板、电脑都能用
- 💾 **本地存储** — 数据保存在浏览器，不泄露隐私

## 🚀 快速开始

### 直接打开（最简单）
下载 `index.html`，双击用浏览器打开即可使用。

### 本地开发服务器
```bash
# 方法1: Python
python -m http.server 8080

# 方法2: Node.js
npx serve

# 方法3: VS Code
# 安装 Live Server 插件，右键 Open with Live Server
```

然后访问 http://localhost:8080

## 🎯 使用流程

```
添加物品 → 填写信息 → 保存成功
    ↓
搜索物品 → 查看位置 → 去拿东西
```

## 🏗️ 技术栈

- **纯前端** — HTML + CSS + JavaScript，无需后端
- **本地存储** — LocalStorage，数据本地保存
- **无依赖** — 原生实现，零第三方库

## 📂 项目结构

```
WhatIsHome-web/
├── index.html    # 主页面（完整应用）
├── README.md     # 项目说明
└── LICENSE       # MIT 开源协议
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License - 随意使用，开心就好
