# 张烨曦 | ZYX

## 关于我

东北大学控制工程专业硕士研究生（A+ 双一流学科），师从柴天佑院士团队。本科毕业于石家庄铁道大学自动化专业（前 1.7%）。

研究方向聚焦**大模型应用开发与工业智能**，具备 RAG 知识库构建、Prompt Engineering、Agent 架构设计、MCP 工具集成等全链路实践经验。熟悉 LoRA/QLoRA 大模型微调范式及 Chroma/FAISS 向量数据库原理。能以 Python + Streamlit 快速搭建可交互的 LLM 应用原型。

### 教育背景

| 时间 | 学校 | 专业 | 备注 |
|------|------|------|------|
| 2024.09 - 2027.06 | 东北大学 | 控制工程 | 硕士，前 17%，柴天佑院士团队 |
| 2020.09 - 2024.06 | 石家庄铁道大学 | 自动化 | 本科，前 1.7% |

### 技术能力

- **大模型应用**: RAG 全链路、Prompt Engineering、Agent/MCP/Skill、Memory 管理
- **模型微调**: LoRA、QLoRA、SFT、Transformer 架构
- **后端 & 数据库**: Python、Streamlit、MySQL、Chroma / FAISS 向量数据库
- **机器学习**: SVM、PCA、K-Means 等经典算法

### 主要成果

- 🏆 中国研究生数学建模竞赛 **国家二等奖**（队长）
- 🏆 美国大学生数学建模竞赛 (MCM) **H 奖**（队长）
- 🏆 "挑战杯"全国大学生课外学术科技作品竞赛 **省特等奖**（负责人）
- 📄 CPCI 收录论文 1 篇（第一作者）
- 📄 软件著作权 2 项 | 发明专利 1 项（第一作者）

---

## 个人项目

### 1. 工业换热教学实验系统知识问答助手

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/SuperZYX4/Experiment-System-Knowledge-QA-Assistant)

基于 **Streamlit + LangChain + Chroma + DashScope** 的 RAG 智能问答平台，面向工业换热教学实验场景，帮助师生快速查询实验装置组成、工艺流程、设备手册与操作规范。

- **功能**: 多格式文档上传（PDF/DOCX/XLSX/CSV/TXT）、分类检索、引用来源展示、会话管理、用户反馈记录、知识管理后台
- **亮点**: 结构化 Prompt 约束输出格式（回答/步骤/风险提示/引用）、基于 SHA256 文档去重、无依据时明确提示而非强行回答、幻觉率降至 5% 以下
- **技术**: LangChain RAG 链路、Chroma 向量库、DashScope DeepSeek 模型、Streamlit 多页面、JSON 本地存储

---

### 2. 大模型新闻热点推送系统

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/SuperZYX4/llm-news-push)

基于 **LangChain + LangGraph** 构建的智能新闻热点推送系统，通过大模型自动搜索、整理和推送热点新闻，支持多节点工作流编排与多渠道消息分发。

- **功能**: 自动化新闻搜索与格式化、多节点 Agent 工作流、FastAPI HTTP 服务、定时调度推送
- **亮点**: LangGraph 状态图编排实现复杂新闻处理流水线、完善的错误分类与恢复机制、支持单节点调试与全流程运行
- **技术**: LangChain 1.0、LangGraph 1.0、OpenAI API、FastAPI、PostgreSQL + SQLAlchemy、S3 存储

---

### 3. 旅游手账地图应用

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/SuperZYX4/travel-journal-map)

基于 **Taro + React + NestJS** 的跨平台旅游手账小程序，支持微信小程序、抖音小程序、H5 多端部署，集成地图标记、行程记录与旅行分享功能。

- **功能**: 地图标记与路线规划、旅行日志与照片管理、多端数据同步、响应式 UI
- **亮点**: Taro 跨平台一套代码多端运行、Zustand 轻量状态管理、Lucide 图标适配小程序环境、NestJS 后端统一 API 响应格式
- **技术**: Taro 4.x、React 18 + TypeScript、Tailwind CSS 4、Zustand、NestJS、pnpm monorepo

---

## 联系方式

- 📧 邮箱：2460926925@qq.com
- 💬 微信：15832899621
- 🐙 GitHub：[SuperZYX4](https://github.com/SuperZYX4)
