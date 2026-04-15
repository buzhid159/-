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





## ❓ 常见问题 (FAQ)
#### Q1: 启动报错 "node 不是内部或外部命令"
A: 请确认解压路径**无中文/空格**，使用 U 盘版自带的 Node 环境。

#### Q2: 换电脑无法运行
A: 确认目标电脑已安装 Git，或直接使用 U 盘内的便携环境。

#### Q3: 数据丢失怎么办
A: 所有数据均存储在 U 盘 `data/` 目录，备份 U 盘即可。




## 🚀 快速启动
### 1. U盘部署
1. 将 U 盘版 OpenClaw 解压到 U 盘根目录
2. 双击 `start.bat` 启动服务
3. 浏览器访问 `http://localhost:18789` 进入控制台

### 2. 模型配置
进入「设置 → 模型设置」，填入：
- API Key：你的大模型密钥
- 模型名称：deepseek-chat（示例）
保存后即可使用。




# OpenClaw U盘便携版 (U-Claw)
> 📍 目录导航
- [项目简介](sslocal://flow/file_open?url=%23%E9%A1%B9%E7%9B%AE%E7%AE%80%E4%BB%8B&flow_extra=eyJsaW5rX3R5cGUiOiJjb2RlX2ludGVycHJldGVyIn0=)
- [快速部署](sslocal://flow/file_open?url=%23%E5%BF%AB%E9%80%9F%E9%83%A8%E7%BD%B2&flow_extra=eyJsaW5rX3R5cGUiOiJjb2RlX2ludGVycHJldGVyIn0=)
- [快速启动](sslocal://flow/file_open?url=%23%E5%BF%AB%E9%80%9F%E5%90%AF%E5%8A%A8&flow_extra=eyJsaW5rX3R5cGUiOiJjb2RlX2ludGVycHJldGVyIn0=)
- [常见问题](sslocal://flow/file_open?url=%23%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98-faq&flow_extra=eyJsaW5rX3R5cGUiOiJjb2RlX2ludGVycHJldGVyIn0=)
