# OpenClaw U盘便携版 (U-Claw)
> 即插即用、无痕运行的AI Agent便携方案

## 📦 项目简介
将完整的Node.js运行时 + OpenClaw核心程序 + 所有依赖 + 配置文件全部打包到U盘，实现：
- ✅ 不安装、不写注册表、不污染系统环境
- ✅ 全部数据/配置/记忆存储在U盘，拔盘无痕
- ✅ 跨Windows/Mac/Linux，换电脑直接用
- ✅ 支持DeepSeek/通义千问等主流大模型

## 🚀 快速部署
### 1. 环境准备
- U盘 ≥8GB（推荐USB3.0）
- 已安装Git环境

### 2. 本地初始化命令
```bash
# 创建README文件
echo "# OpenClaw U-Claw" >> README.md
# 初始化本地Git仓库
git init
# 把README加入暂存区
git add README.md
# 提交到本地仓库
git commit -m "first commit"
# 把默认分支重命名为main（GitHub标准）
git branch -M main
# 绑定远程仓库
git remote add origin https://github.com/buzhid159/-.git
# 第一次推送，把本地main分支推到远程
git push -u origin main
