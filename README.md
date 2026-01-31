# OpenClaw Showcase

🚀 **OpenClaw 展示站** - 教程、技能包与实战案例

[在线预览](https://openclaw.show) | [OpenClaw 主项目](https://github.com/openclaw/openclaw)

---

## 📖 关于本项目

这是 OpenClaw 个人 AI 助手平台的官方展示站，提供：

- 📚 **快速入门教程** - 从安装到配置的完整指南
- 🧩 **技能包库** - 社区贡献的技能包和插件
- 💡 **实战案例** - 真实用户的使用场景和创意分享
- 🌐 **在线展示** - 美观的单页介绍，了解 OpenClaw 的核心功能

## 🎯 什么是 OpenClaw？

OpenClaw 是一个开源的自托管个人 AI 助手平台，让你在自己的设备上运行 AI 助手，通过日常使用的消息应用与它交互。

### 核心特点

- 🔒 **隐私优先** - 本地运行，数据完全由你掌控
- ⚡ **快速响应** - 无需等待云端，即时处理
- 💬 **多渠道接入** - 支持 WhatsApp、Telegram、Discord、Slack、Signal、iMessage 等 10+ 个平台
- 🔌 **可扩展** - 30+ 官方插件，支持自定义开发
- 🌐 **跨平台** - macOS、iOS、Android、Linux、Windows WSL

## 📂 项目结构

```
openclaw-show/
├── index.html          # 主展示页面
├── tutorials/          # 教程文档（即将推出）
├── skills/             # 技能包库（即将推出）
└── showcases/          # 用户案例（即将推出）
```

## 🚀 本地预览

```bash
# 克隆仓库
git clone https://github.com/AICodeOS/openclaw-show.git
cd openclaw-show

# 启动本地服务器
python3 -m http.server 8000

# 访问 http://localhost:8000
```

## 🌐 部署

### Nginx 配置示例

```nginx
server {
    listen 80;
    server_name openclaw.show;

    root /path/to/openclaw-show;
    index index.html;

    location / {
        try_files $uri $uri/ =404;
    }
}
```

### GitHub Pages

本项目支持 GitHub Pages 部署：

1. 进入仓库 Settings → Pages
2. Source 选择 `main` 分支
3. 保存后即可通过 `https://aicodeOS.github.io/openclaw-show/` 访问

## 🤝 贡献指南

我们欢迎社区贡献！

### 贡献教程

1. Fork 本仓库
2. 在 `tutorials/` 目录下创建你的教程
3. 提交 Pull Request

### 分享技能包

1. 在 `skills/` 目录下添加你的技能包
2. 包含使用说明和安装方法
3. 提交 Pull Request

### 展示你的案例

1. 在 `showcases/` 目录下分享你的使用案例
2. 包含场景描述、配置方法、效果展示
3. 提交 Pull Request

## 📝 路线图

- [x] 主展示页面
- [ ] 快速入门教程
- [ ] 进阶配置指南
- [ ] 技能包市场
- [ ] 用户案例展示
- [ ] 多语言支持
- [ ] 交互式演示

## 🔗 相关链接

- [OpenClaw 主项目](https://github.com/openclaw/openclaw)
- [官方文档](https://docs.openclaw.ai)
- [问题反馈](https://github.com/openclaw/openclaw/issues)

## 📄 许可证

本项目采用与 OpenClaw 主项目相同的开源许可证。

---

**Made with ❤️ by OpenClaw Community**
