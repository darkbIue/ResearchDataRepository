# agent 评估基准和系统平台调研

## agent 评估基准表格
| 序号 | 测试基准 | 评价策略 | 适用场景 | 序号 | 测试基准 | 评价策略 | 适用场景 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | AgentBench[1] | 多重任务 | 通用评估 | 10 | ReAct[17] | 环境模拟 | 推理能力评估 |
| 2 | AgentBoard[2] | 多重任务 | 通用评估 | 11 | DEPS[18] | 环境模拟 | 交互评估 |
| 3 | SuperClue-Agent[3] | 多重任务 | 基础能力评估 | 12 | ToolBench[8] | 多重任务 | 工具学习能力评估 |
| 4 | ToolEyes[4] | 多重任务 | 工具学习能力评估 | 13 | GITM[19] | 环境模拟 | 行动评估 |
| 5 | TravelPlanner[10] | 环境模拟 | 规划能力评估 | 14 | Voyager[20] | 环境模拟 | 行动评估 |
| 6 | ML-Bench[9] | 软件测试 | 代码任务能力评估 | 15 | SocKET[11] | 社会评估+多重任务 | 社交能力评估 |
| 7 | T-Eval[14] | 多重任务 | 工具学习能力评估 | 16 | MobileEnv[12] | 环境模拟+多重任务 | 交互能力评估 |
| 8 | IGLU[15] | 环境模拟 | 交互评估 | 17 | Clembench[21] | 环境模拟+多重任务 | 对话能力评估 |
| 9 | WebShop[16] | 环境模拟+多重任务 | 检索能力评估 | 18 | Dialop[22] | 社会评估 | 对话能力评估 |
## agent 系统平台表格


### 单智能体架构
| 平台名称 | 简介 | 应用领域 |
| ---- | ---- | ---- |
| 百度千帆 AgentBuilder[1] | 基于文心大模型的智能体平台，提供零代码和低代码开发。 | 企业服务、个人助理 |
| 讯飞的星火友伴[2] | 讯飞科技推出的专注于虚拟人格 GPTs 应用的创新平台。 | 虚拟人格、教育、娱乐 |
| 智谱[3] | 智谱清言推出的 Agent 生成器，支持通过 API 调用方式灵活使用智能体。 | 教育、个人助理、企业服务 |
| BabyAGI[4] | 早期 agent 实践，具有任务优先级排序模块。 | 任务管理、个人助理 |
| AutoGPT[5] | 自动化 GPT，用于自动化任务执行和决策。 | 自动化、企业服务 |
| HuggingGPT[6] | 集成了多种 AI 模型的智能体，用于提供综合性服务 | 企业服务、教育、娱乐 |
| GPT-Engineer[7] | 专注于工程和开发任务的智能体。 | 软件开发、工程服务 |
| Samantha[8] | 灵感来源于电影 her，基于 GPT4-V 不断从环境中获取图像和语音信息，会自主发起提问。 | 个人助理、情感交流 |
| AppAgent[9] | 基于 ground-dino 以及 gpt view 模型做多模态处理的 Agent。 | 移动应用、多模态交互 |
| OS-Copilot[10] | 操作系统中的智能体，辅助用户进行系统操作和任务管理。 | 操作系统辅助、任务管理 |

### 多智能体架构
| 平台名称 | 简介 | 应用领域 |
| ---- | ---- | ---- |
| 字节 COZE[11] | 字节跳动的 AI Bot 开发平台，加速智能聊天机器人的设计与部署流程。 | 聊天机器人、企业服务、个人助理 |
| SkyAgents(昆仑万维)[12] | 昆仑万维的 AI Agents 构建平台，旨在重塑智能应用的创造边界。 | 企业服务、个人助理、智能应用创造 |
| 阿里云魔搭社区[13] | 由阿里达摩院推出的 AI 模型社区。 | 开源大模型、企业服务、个人助理 |
| 华为云 AI Agent[14] | 华为云的 AI Agent 技术实践，包括构建企业词表、外挂知识库整合等。 | 企业服务、专业领域、智能设备管理 |
| MetaGPT[15] | 集成多种 AI 技术，提供高度定制化的智能体服务。 | 软件开发、数据分析、自动化 |
| AutoGen[16] | 自动代码生成和优化平台，提高开发效率。 | 企业服务、教育、娱乐 |
| ChatDEV[17] | 专注于开发任务的聊天机器人，提供编程建议和代码片段。 | 软件开发、编程教育 |
| GPTeam[18] | 团队协作智能体，优化团队工作流程和项目管理。 | 企业服务、项目管理、团队协作 |
| TaskWeaver[19] | 任务管理和自动化平台，智能分配和协调任务。 | 任务管理、自动化、企业服务 |
| 微软 UFO[20] | Windows 系统下的用户界面交互智能体。 | 企业服务、个人助理 |


**参考文献**

1. [百度智能云千帆大模型平台. ModelBuilder](https://qianfan.cloud.baidu.com/?track=33dcf5d1abd0f1309604ab9c20431a1042e54d059042bac8, 2024)
2. [AI工具再升级:全新友伴功能赋予AI人物更生动的个性和对话能力](https://zhuanlan.zhihu.com/p/663006610, 2024)
3. [智谱AI](https://www.zhipuai.cn/, 2024)   
4. [Yohei Nakajima. Birth of BabyAGI](https://yoheinakajima.com/birth-of-babyagi/, 2024)
5. [Significant-Gravitas. AutoGPT: build & use AI agents](https://github.com/Significant-Gravitas/AutoGPT, 2024)
6. [Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang. HuggingGPT: Solving AI。 Tasks with ChatGPT and its Friends in Hugging Face](https://arxiv.org/abs/2303.17580, 2023)
7. [AntonOsika. gpt-engineer](https://github.com/AntonOsika/gpt-engineer, 2024)
8. [BRlkl. AGI-Samantha](https://github.com/BRlkl/AGI-Samantha, 2024)
9. [Chi Zhang, Zhao Yang, Jiaxuan Liu, Yucheng Han, Xin Chen, Zebiao Huang, Bin Fu, Gang Yu. AppAgent: Multimodal Agents as Smartphone Users](https://arxiv.org/abs/2312.13771, 2023)
10. [Zhiyong Wu, Chengcheng Han, Zichen Ding, et al. OS-Copilot: Towards Generalist Computer Agents with Self-Improvement](https://arxiv.org/pdf/2402.07456, 2024)
11. [字节Coze](https://www.coze.cn, 2024)
12. [天工平台](https://model-platform.tiangong.cn/, 2024)
13. [魔搭](https://www.modelscope.cn/, 2024)
14. [华为云. 盘古大模型](https://www.huaweicloud.com/product/pangu.html, 2024)
15. [MetaGPT: 多智能体框架](https://docs.deepwisdom.ai/main/zh/guide/get_started/introduction.html, 2024)
16. [Qingyun Wu, Gagan Bansal, Jieyu Zhang, et al. AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/pdf/2308.08155, 2023)
17. [Chen Qian, Wei Liu, Hongzhang Liu, et al. ChatDev: Communicative Agents for Software Development](https://arxiv.org/pdf/2307.07924, 2023)
18. [GPTeam: A multi-agent simulation​](https://blog.langchain.dev/gpteam-a-multi-agent-simulation/, 2024)
19. [TaskWeaver]([https://arxiv.org/pdf/2402.07456, 2024](https://microsoft.github.io/TaskWeaver/docs/overview))
20. [Chaoyun Zhang, Liqun Li, Shilin He, et al. UFO: A UI-Focused Agent for Windows OS Interaction](https://arxiv.org/pdf/2402.07939, 2024)