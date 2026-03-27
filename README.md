# Awesome 医疗 AI 项目 🏥🤖🇨🇳

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![最后更新](https://img.shields.io/badge/最后更新-2026--03--27-blue.svg)](#)

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
| [MING](https://github.com/MediaBrain-SJTU/MING) | ![](https://img.shields.io/github/stars/MediaBrain-SJTU/MING?style=flat-square) | 上海交大 MediaBrain | 中文医疗问诊大模型。支持医疗问答和多轮问诊，并持续开源 MING-MOE、评测与临床 agent 相关工作。 |
| [BianQue](https://github.com/scutcyr/BianQue) | ![](https://img.shields.io/github/stars/scutcyr/BianQue?style=flat-square) | 华南理工 | 主动健康大模型基座中的中文健康对话模型，强调多轮问询链、慢病与心理咨询场景，配套千万级健康对话数据。 |
| [QiZhenGPT](https://github.com/CMKRG/QiZhenGPT) | ![](https://img.shields.io/github/stars/CMKRG/QiZhenGPT?style=flat-square) | 浙大 / 启真医学 | 基于启真医学知识库构建的中文医疗大模型，已扩展为 MedCopilot 并落地医院智慧助手场景。 |
| [HuatuoGPT-II](https://github.com/FreedomIntelligence/HuatuoGPT-II) | ![](https://img.shields.io/github/stars/FreedomIntelligence/HuatuoGPT-II?style=flat-square) | 港中文深圳 | HuatuoGPT 第二代：一阶段医疗域适配，开源 7B/13B/34B 模型、训练数据与评测代码。 |
| [Taiyi-LLM](https://github.com/DUTIR-BioNLP/Taiyi-LLM) | ![](https://img.shields.io/github/stars/DUTIR-BioNLP/Taiyi-LLM?style=flat-square) | 大工 BioNLP | 中英双语生物医学大模型 Taiyi 2，覆盖 13 类 biomedical 任务，开放模型、数据和 Demo。 |
| [Huatuo-Llama-Med-Chinese](https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese) | ![](https://img.shields.io/github/stars/SCIR-HI/Huatuo-Llama-Med-Chinese?style=flat-square) | 哈工大 SCIR | 基于中文医学知识的指令微调医疗大模型系列，开源模型、训练代码、论文和双语文档。 |
| [Med-ChatGLM](https://github.com/SCIR-HI/Med-ChatGLM) | ![](https://img.shields.io/github/stars/SCIR-HI/Med-ChatGLM?style=flat-square) | 哈工大 SCIR | 基于中文医学知识和知识图谱构建的 ChatGLM 医疗微调模型。开源训练代码、数据构建脚本和模型下载。 |
| [DoctorGLM](https://github.com/xionghonglin/DoctorGLM) | ![](https://img.shields.io/github/stars/xionghonglin/DoctorGLM?style=flat-square) | 开源社区 | 基于 ChatGLM-6B 的中文问诊模型，覆盖多科室问答数据，提供论文、演示页与交互测试代码。 |
| [ChatMed](https://github.com/michael-wzhu/ChatMed) | ![](https://img.shields.io/github/stars/michael-wzhu/ChatMed?style=flat-square) | 开源社区 | 面向日常在线问诊的中文医疗大模型。开源 50 万+ 问诊数据、LoRA 权重和训练脚本。 |
| [Sunsimiao](https://github.com/X-D-Lab/Sunsimiao) | ![](https://img.shields.io/github/stars/X-D-Lab/Sunsimiao?style=flat-square) | X-D Lab | 孙思邈中文医疗大模型系列。提供权重、Demo、QLoRA 训练/部署说明，强调安全可靠的中文医疗对话能力。 |
| [ShenNong-TCM-LLM](https://github.com/michael-wzhu/ShenNong-TCM-LLM) | ![](https://img.shields.io/github/stars/michael-wzhu/ShenNong-TCM-LLM?style=flat-square) | 开源社区 | 面向中医药知识问答与传承的大模型，公开中医知识图谱、自指令数据构建方法和模型资源。 |
| [HuangDi](https://github.com/Zlasejd/HuangDi) | ![](https://img.shields.io/github/stars/Zlasejd/HuangDi?style=flat-square) | 开源社区 | 面向中医古籍知识问答的大模型。含继续预训练语料、50 万+ 指令数据构建说明和训练脚本。 |
| [CMLM-ZhongJing](https://github.com/pariskang/CMLM-ZhongJing) | ![](https://img.shields.io/github/stars/pariskang/CMLM-ZhongJing?style=flat-square) | CMLM | 面向中医的专家知识引导大模型，提供 13.5 万+ 专业指令、论文、权重和 Colab 部署示例。 |
| [Zhongjing](https://github.com/SupritYoung/Zhongjing) | ![](https://img.shields.io/github/stars/SupritYoung/Zhongjing?style=flat-square) | 开源社区 | 首个完整覆盖预训练、SFT 和 RLHF 流程的中文医疗大模型之一，公开真实多轮医患数据集 CMtMedQA 与 AAAI 2024 论文代码。 |
| [TCMLLM](https://github.com/2020MEAI/TCMLLM) | ![](https://img.shields.io/github/stars/2020MEAI/TCMLLM?style=flat-square) | 2020MEAI | 聚焦中医临床辅助诊疗与处方推荐的指令微调大模型，附 68k 数据样本和批量推理脚本。 |
| [MedChatZH](https://github.com/tyang816/MedChatZH) | ![](https://img.shields.io/github/stars/tyang816/MedChatZH?style=flat-square) | 开源社区 | 基于 Baichuan-7B 的中文医疗问诊模型，兼顾中西医对话，提供数据集、模型和 Web/脚本部署方式。 |

---

## 医学影像 AI

> 医学影像分析、诊断、分割等 AI 项目。

| 项目 | Stars | 说明 |
|------|-------|------|
| [MedRAX](https://github.com/bowang-lab/MedRAX) | ![](https://img.shields.io/github/stars/bowang-lab/MedRAX?style=flat-square) | **ICML 2025**。胸部 X 光 AI 解读。集成 CheXagent、LLaVA-Med、MedSAM 等多模型。需 GPU。 |
| [EasyLung](https://github.com/TommyZihao/EasyLung) | ![](https://img.shields.io/github/stars/TommyZihao/EasyLung?style=flat-square) | 从 X 光胸片中 AI 识别肺炎及病原体种类。包含网页、**微信小程序**、APP。 |
| [XrayGLM](https://github.com/WangRongsheng/XrayGLM) | ![](https://img.shields.io/github/stars/WangRongsheng/XrayGLM?style=flat-square) | 中文胸部 X 光多模态模型，提供中文化报告数据集、训练权重和微调实践。 |
| [Qilin-Med-VL](https://github.com/williamliujl/Qilin-Med-VL) | ![](https://img.shields.io/github/stars/williamliujl/Qilin-Med-VL?style=flat-square) | 中文医疗视觉语言大模型，配套 100 万级 ChiMed-VL 图文数据和两阶段训练脚本。 |
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
| [智能医疗助手系统](https://github.com/Kevin6giao/zhinengyiliao) | ![](https://img.shields.io/github/stars/Kevin6giao/zhinengyiliao?style=flat-square) | 基于 LangChain4j + Vue3 的智能医疗助手。支持 AI 问答、分导诊、挂号预约/取消和 Pinecone RAG 知识库，前后端分离。 |
| [MedChatAI](https://github.com/huboyang040911/MedChatAI) | ![](https://img.shields.io/github/stars/huboyang040911/MedChatAI?style=flat-square) | 医疗智能对话系统。FastAPI + Vue3，支持 Dify 知识库检索、图片 OCR、流式响应、用户管理和个性化病史参考。 |

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
