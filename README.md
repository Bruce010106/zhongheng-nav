# 江苏中衡专业办公导航 / Jiangsu Zhongheng Professional Navigation
## 📖 项目简介 / Introduction
本项目是为江苏中衡定制开发的专业办公导航平台 。它整合了招投标代理、造价咨询、政府采购及日常办公所需的各类核心权威网站与工具，旨在提升团队的信息获取效率和业务合规性 。

This project is a customized professional navigation portal for Jiangsu Zhongheng. It integrates authoritative websites and tools required for bidding agency, cost engineering, and procurement to enhance efficiency and compliance.


## ✨ 核心板块 / Key Features
根据业务逻辑，导航分为以下六大模块 / The portal is organized into six functional modules:

- 核心数据与询价 (Core Data & Pricing): 包含造价信息、材料价格、定额查询等 。
- 政策法规与信用 (Policy & Regulations): 提供住建部政策、标准规范、合同范本及企业信用查询 。
- 政府采购与招投标 (Procurement & Bidding): 覆盖国家及地方政采网、军队采购及商机雷达 。
- 专业算量与管理 (Cost Management): 整合广联达、鲁班等专业软件及在线项目管理工具 。
- 效率协作与云盘 (Efficiency & Collaboration): 包含文档协作、大文件传输及企业通讯 。
- 办公神器与计算 (Productivity Tools): 提供科学计算器、OCR 扫描、PDF 处理等实用工具 。

## 🛠️ 技术栈 / Tech Stack
- HTML5 / CSS3
- Tailwind CSS: 用于现代化的响应式布局设计。
- GitHub Pages: 用于静态网站的托管与发布。

## 🚀 开发者指南 / Development Guide
**CI/CD 流程 / CI/CD Workflow**
本项目已集成 GitHub Actions 自动部署流程。任何提交到 main 分支的代码都会自动触发网站更新。

1. 克隆仓库 / Clone Repository:
Bash
'''git clone https://github.com/Bruce010106/zhongheng-nav.git'''
2. 开发流程 / Development Flow: 推荐使用功能分支进行更新：
Bash
'''
git checkout -b feat/update-links
# 修改 index.html / Edit index.html
git add .
git commit -m "feat: 增加新的造价查询链接"
git push origin feat/update-links'''
3. 合并与部署 / Merge & Deploy: 在 GitHub 上发起 Pull Request，合并至 main 后，CI/CD 任务将自动运行 。

## 🌐 访问地址 / Access Link
点击此处访问在线版本 / Click below to access the live site: 👉 https://Bruce010106.github.io/zhongheng-nav/

## 🤝 贡献与反馈 / Contribution
如有新的网址建议或界面优化想法，请联系项目维护者。 For any suggestions or UI feedback, please contact the maintainer.