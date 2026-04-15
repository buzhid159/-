# OpenClaw U盘便携版 (U-Claw)
> 📍 目录导航
- [项目简介](#项目简介)
- [快速部署](#快速部署)
- [快速启动](#快速启动)
- [常见问题](#常见问题-faq)

---

## 项目简介
OpenClaw U盘便携版（U-Claw）是将完整的 Node.js 运行环境 + OpenClaw 核心程序打包到 U 盘的 AI Agent 工具。

✅ 不安装、不写注册表、不污染系统环境  
✅ 所有数据、配置、记忆全部保存在 U 盘  
✅ 即插即用，换电脑直接运行  
✅ 支持 DeepSeek / 通义千问 / 讯飞星火 等大模型  

---

## 快速部署
### 本地初始化命令
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
