# Awesome 医疗 AI 项目 🏥🤖🇨🇳

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![最后更新](https://img.shields.io/badge/最后更新-2026--03--22-blue.svg)](#)

> 🔧 **找 AI Agent 技能和 MCP 服务器？** 请看 [awesome-medical-ai-skills-cn](https://github.com/JuneYaooo/awesome-medical-ai-skills-cn) — 可安装到 Claude Code、Cursor、OpenClaw 等平台的技能

> 🌍 **International Edition** See [awesome-medical-ai](https://github.com/JuneYaooo/awesome-medical-ai)

> 精选**国内**医疗 AI 开源项目合集 — 大模型、影像 AI、临床系统、NLP、多智能体等。

---

## 目录

- [中文医疗大模型](#中文医疗大模型)
- [医学影像 AI](#医学影像-ai)
- [电子病历与临床系统](#电子病历与临床系统)
- [医疗 NLP](#医疗-nlp)
- [多智能体医疗系统](#多智能体医疗系统)
- [资源合集](#资源合集)
- [国内急需但尚缺的方向](#-国内急需但尚缺的方向)

---

## 中文医疗大模型

> 国内团队开发的医疗领域大模型，可作为 Agent 底座或独立使用。

| 项目 | Stars | 团队 | 说明 |
|------|-------|------|------|
| [HuatuoGPT](https://github.com/FreedomIntelligence/HuatuoGPT) | ![](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT?style=flat-square) | 港中文深圳 | 华佗 GPT — 面向医疗场景的开源中文医疗大模型。支持问诊对话、医学知识问答。 |
| [HuatuoGPT-o1](https://github.com/FreedomIntelligence/HuatuoGPT-o1) | ![](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT-o1?style=flat-square) | 港中文深圳 | 医疗领域复杂推理能力，Medical o1 思路。 |
| [DISC-MedLLM](https://github.com/FudanDISC/DISC-MedLLM) | ![](https://img.shields.io/github/stars/FudanDISC/DISC-MedLLM?style=flat-square) | 复旦 DISC | 面向医疗健康对话的大语言模型。智能问诊、医疗知识问答、病历结构化。 |

---

## 医学影像 AI

> 医学影像分析、诊断、分割等 AI 项目。

| 项目 | Stars | 说明 |
|------|-------|------|
| [MedRAX](https://github.com/bowang-lab/MedRAX) | ![](https://img.shields.io/github/stars/bowang-lab/MedRAX?style=flat-square) | **ICML 2025**。胸部 X 光 AI 解读。集成 CheXagent、LLaVA-Med、MedSAM 等多模型。需 GPU。 |
| [EasyLung](https://github.com/TommyZihao/EasyLung) | ![](https://img.shields.io/github/stars/TommyZihao/EasyLung?style=flat-square) | 从 X 光胸片中 AI 识别肺炎及病原体种类。包含网页、**微信小程序**、APP。 |
| [liver_cancer_classify](https://github.com/wuwusky/liver_cancer_classify) | — | 肝癌影像 AI 诊断（3D-Conv 深度学习）。 |
| [Lambar_Spine_Slicer](https://github.com/Keyon-2580/Lambar_Spine_Slicer) | — | 腰椎影像智能分割可视化系统。Vue+Django+3DUNet。 |
| [paddle-fl-gui](https://github.com/yyyanbj/paddle-fl-gui) | — | 基于 PaddleFL 的联邦学习医疗影像识别 GUI。百度飞桨框架。 |

---

## 电子病历与临床系统

> 开源医院信息系统、电子病历编辑器等。

| 项目 | Stars | 说明 |
|------|-------|------|
| [SoDiaoEditor](https://github.com/tlzzu/SoDiaoEditor) | ![](https://img.shields.io/github/stars/tlzzu/SoDiaoEditor?style=flat-square) | 通用结构化文档编辑器，**被多家三甲医院采用作为电子病历编辑器**。支持模板、结构化数据录入。持续维护中。 |
| [HIS（ZainZhao）](https://github.com/ZainZhao/HIS) | ![](https://img.shields.io/github/stars/ZainZhao/HIS?style=flat-square) | 医院信息系统。门诊/药房/财务/患者管理工作站。Spring Boot。 |
| [HIS（TANGKUO）](https://github.com/TANGKUO/HIS) | ![](https://img.shields.io/github/stars/TANGKUO/HIS?style=flat-square) | 医院信息系统。临床诊疗、药品管理、财务管理、患者管理。 |
| [云医疗管理系统](https://github.com/Rain-Ricky/cloud) | ![](https://img.shields.io/github/stars/Rain-Ricky/cloud?style=flat-square) | 网上挂号、在线问诊、诊断报告查询、费用缴纳。Spring Boot + 前后端分离。 |

---

## 医疗 NLP

> 中文医疗自然语言处理项目。

| 项目 | Stars | 说明 |
|------|-------|------|
| [Chinese-clinical-NER](https://github.com/MenglinLu/Chinese-clinical-NER) | ![](https://img.shields.io/github/stars/MenglinLu/Chinese-clinical-NER?style=flat-square) | CCKS2019 中文命名实体识别：从医疗文本中识别疾病、解剖部位、影像检查、实验室检验、手术和药物 6 种实体。 |

---

## 多智能体医疗系统

> 多智能体医疗 AI 框架和研究系统。

| 项目 | Stars | 说明 |
|------|-------|------|
| [cyber-doctor（赛博华佗）](https://github.com/Warma10032/cyber-doctor) | ![](https://img.shields.io/github/stars/Warma10032/cyber-doctor?style=flat-square) | 基于多模态大模型的多功能医疗智能体。支持本地部署，可接入医疗知识图谱。疾病初诊、病历分析、专业知识问答。 |
| [MedgeClaw](https://github.com/xjtulyc/MedgeClaw) | ![](https://img.shields.io/github/stars/xjtulyc/MedgeClaw?style=flat-square) | 西安交大 — 生物医学 AI **研究编排助手**。通过对话调用 RNA-seq、药物发现、临床分析等 140+ 科学技能。基于 Claude Code + OpenClaw。 |
| [Multi-Agent-Medical-Assistant](https://github.com/souvikmajumder26/Multi-Agent-Medical-Assistant) | ![](https://img.shields.io/github/stars/souvikmajumder26/Multi-Agent-Medical-Assistant?style=flat-square) | 多智能体诊断和医疗研究聊天机器人。 |
| [medgraph-ai](https://github.com/asanmateu/medgraph-ai) | — | Neo4j 知识图谱 + RAG 的医疗问答。LangChain + FastAPI。 |
| [SOLVE-Med](https://github.com/PRAISELab-PicusLab/SOLVE-Med) | — | 面向隐私的多智能体医疗问答，可离线运行。 |

---

## 资源合集

| 资源 | Stars | 说明 |
|------|-------|------|
| [Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH) | ![](https://img.shields.io/github/stars/yzfly/Awesome-MCP-ZH?style=flat-square) | MCP 中文资源精选合集 |
| [ai-guide（鱼皮）](https://github.com/liyupi/ai-guide) | ![](https://img.shields.io/github/stars/liyupi/ai-guide?style=flat-square) | AI 资源大全 + 教程。含 OpenClaw/Claude Code 教程、Skills 使用指南。 |
| [Awesome-LLM-Healthcare](https://github.com/mingze-yuan/Awesome-LLM-Healthcare) | ![](https://img.shields.io/github/stars/mingze-yuan/Awesome-LLM-Healthcare?style=flat-square) | LLM 在医疗领域的论文合集。 |

---

## 🔴 国内急需但尚缺的方向

| 方向 | 需求场景 | 难度 |
|------|---------|------|
| 🏥 **NMPA 药品/器械查询** | 查询国家药监局药品注册信息、器械注册状态 | ⭐⭐ |
| 💊 **国家基本药物目录** | 查询基药目录、医保目录、集采药品信息 | ⭐⭐ |
| 📋 **DRG/DIP 分组辅助** | 辅助 DRG/DIP 编码分组和费用预测 | ⭐⭐⭐ |
| 🏥 **互联网医院接口** | 对接微医、好大夫、丁香园等平台 API | ⭐⭐⭐ |
| 📱 **华为/小米健康数据** | 华为运动健康、小米健康 API 数据读取 | ⭐⭐⭐ |
| 🌿 **中医辨证论治 Agent** | 基于中医理论的智能辨证和方剂推荐 | ⭐⭐⭐⭐ |
| 🧬 **国内基因检测数据** | 对接微基因、23魔方等国内基因检测数据 | ⭐⭐⭐ |
| 📊 **卫健委数据接口** | 查询全国卫生统计、传染病疫情等公开数据 | ⭐⭐ |

**欢迎社区贡献！** 如果你正在开发以上方向的项目，请提交 PR。

---

## 姊妹仓库

| 仓库 | 说明 |
|------|------|
| [awesome-medical-ai-skills](https://github.com/JuneYaooo/awesome-medical-ai-skills) | 🔧 医疗 AI Agent Skills & MCP 服务器（国际版） |
| [awesome-medical-ai-skills-cn](https://github.com/JuneYaooo/awesome-medical-ai-skills-cn) | 🔧 医疗 AI Agent Skills & MCP 服务器（国内版） |
| [awesome-medical-ai](https://github.com/JuneYaooo/awesome-medical-ai) | 🌍 医疗 AI 项目合集（国际版） |

---

## ⚠️ 免责声明

> 本列表中的所有项目仅供**信息参考和研究目的**。它们**不是**经过验证的临床工具，**不应**用于实际的医疗诊断或治疗决策。请始终咨询合格的医疗专业人员获取医疗建议。

---

## 参与贡献

欢迎贡献！提交格式：

```markdown
| [项目名](链接) | Stars | 一句话说明 |
```

### 💡 用过好用的医疗 AI 项目？推荐给大家！

[提交 Issue](../../issues/new?title=推荐:+项目名称) 分享你的使用体验。

---

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

本列表以 [CC0 1.0 通用](LICENSE) 发布。
