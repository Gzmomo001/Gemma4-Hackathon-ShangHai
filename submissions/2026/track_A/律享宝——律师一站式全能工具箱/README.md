# 律享宝智能法律助手
## 项目背景
律享宝是一款基于Gemma4大模型的一站式法律文书生成平台，针对律师和普通用户在法律文书撰写中存在的"格式不规范、内容不专业、耗时耗力"等痛点，提供90+种标准化法律文书模板，支持一键生成符合最高法和司法部最新规范的PDF/Word文档。

## 核心功能
✅ **90+标准化法律文书模板**：覆盖民事诉讼、法律援助、律师办案辅助三大类
✅ **智能表单生成**：根据模板自动生成动态表单，用户只需填写关键信息
✅ **一键导出**：支持导出PDF、Word两种格式，直接用于法院提交
✅ **Gemma4智能辅助**：集成Gemma4大模型，提供法律条文引用、事实理由润色功能
✅ **草稿保存**：自动保存用户填写的表单数据，支持随时继续编辑
✅ **用户管理**：支持用户注册登录，管理个人历史文书

## 技术栈
- **后端**：Spring Boot 3.2.5 + FreeMarker 2.3.32 + MySQL 8.0 + LibreOffice 7.5
- **前端**：Vue 3.4 + Vite 5.2 + Element Plus 2.7 + Vue Router 4.3 + Pinia 2.1
- **AI能力**：Google Gemma 4 4B + LangChain
- **部署**：Docker + Docker Compose

## 环境安装步骤
### 1. 一键部署（推荐）
```bash
# 克隆项目
git clone https://github.com/你的用户名/Gemma4-Hackathon-ShangHai.git
cd Gemma4-Hackathon-ShangHai/submissions/2026/A/律享宝智能法律助手

# 启动所有服务
docker-compose up -d
