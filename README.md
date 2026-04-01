# AI Agent 全局解决方案映射表

> 按天累积，每次发布后自动追加新条目。维度：项目名称 / 链接 / 解决的核心问题 / 适用场景

| 项目名称 | 链接 | 解决的核心问题 | 适用场景 | 收录日期 |
|---|---|---|---|---|
| Deer-Flow | https://github.com/bytedance/deer-flow | 单 Agent 无法完成需要多步骤、多子任务并行的长时间复杂任务 | 竞品调研自动化、代码生成+测试、批量数据采集与汇总 | 2026-03-24 |
| browser-use | https://github.com/browser-use/browser-use | AI 无法操控真实浏览器进行网页交互（点击/填表/提交） | 网页数据抓取、自动化表单填写、需要登录才能访问的信息采集 | 2026-03-24 |
| TradingAgents | https://github.com/TauricResearch/TradingAgents | 单一模型做金融决策缺乏多角度博弈验证，容易偏颇 | 量化策略研究、多维度投资分析辅助（非直接交易，仅研究用途） | 2026-03-24 |
| everything-claude-code | https://github.com/AFFAAN-M/everything-claude-code | AI 编程助手跨会话失忆、缺乏项目上下文、操作无安全边界 | 长期迭代的工程项目、团队共享 AI 工作规范、企业级 AI 编程安全管控 | 2026-03-24 |
| LangGraph | https://langchain-ai.github.io/langgraph/ | Agent 执行逻辑无法支持循环、条件分支和并行，复杂流程难以建模 | 多 Agent 编排框架底层、需要状态管理的复杂 Agent 系统 | 2026-03-24 |
| MetaClaw | https://github.com/aiming-lab/MetaClaw | LLM Agent 部署后静态，无法从真实对话中自动进化与学习 | SaaS 产品内嵌自进化 Agent；无 GPU 也可用 skills_only 模式；生产环境持续改进 | 2026-03-25 |
| DeerFlow 2.0 | https://github.com/bytedance/deer-flow | 单 Agent 上下文溢出，无法完成需要小时级执行的复杂多步骤任务 | 深度研究报告自动生成、代码端到端自动化、IM 触发定时工作流 | 2026-03-25 |
| Nemotron-Cascade 2 | https://arxiv.org/abs/2603.19220 | 多任务 RL 训练中的灾难性遗忘问题，同等参数效率极低 | 低成本高性能推理部署；数学/代码 Agent；作为蒸馏目标模型 | 2026-03-25 |
| OpenResearcher | https://github.com/TIGER-AI-Lab/OpenResearcher | 深度研究 Agent 依赖昂贵外部 API，训练流程不可复现、无法私有化 | 金融/医疗/法律私有化深度研究；企业知识库（Confluence/SharePoint）智能问答 | 2026-03-25 |
| Hermes-Agent | https://github.com/NousResearch/Hermes-Agent | AI 助手跨会话失忆，无法积累用户偏好与技能 | 需要长期记忆的个人 AI 助手；Telegram/Discord AI 机器人；自托管可进化 Agent | 2026-03-26 |
| Supermemory | https://github.com/supermemoryai/supermemory | RAG 无状态、无法追踪用户随时间变化的事实 | 多用户 AI 产品的记忆 API；替代或补充 RAG 的用户记忆层；MCP 接入 Cursor/Claude | 2026-03-26 |
| SpecEyes（论文） | https://arxiv.org/abs/2603.23483 | 多模态 Agent 工具调用链串行延迟高，并发吞吐量低 | Agentic MLLM 推理加速；减少视觉工具 API 调用成本；边缘端小模型+云端大模型混部 | 2026-03-26 |
| LongCat-Flash-Prover（论文） | https://arxiv.org/abs/2603.21065 | LLM 无法完成 Lean4 形式化定理证明，推理深度不足 | 代码/协议形式化验证；数学推理 Agent；大型 MoE 模型长序列 RL 训练参考 | 2026-03-26 |
| UI-Voyager（论文） | https://arxiv.org/abs/2603.24533 | GUI Agent 无法从失败经历中学习，长步骤任务成功率低 | Android 自动化测试；RPA 流程自动化；无障碍辅助工具；4B 小模型超人类水平 | 2026-03-27 |
| EVA（论文） | https://arxiv.org/abs/2603.22918 | 多模态 LLM 处理长视频时 Token 爆炸，被动感知效率低 | 长视频问答；视频内容检索；视频 RAG 降本；SFT→KTO→GRPO 训练管线参考 | 2026-03-27 |
| dexter | https://github.com/virattt/dexter | AI 金融分析无自我验证能力，分析结论无法追溯审计 | 基本面财报分析；量化研究辅助；ReAct Agent 学习案例；支持 Ollama 本地模型 | 2026-03-27 |
| oh-my-claudecode | https://github.com/Yeachan-Heo/oh-my-claudecode | Claude Code 单 Agent 无法完成需要多角色协同的复杂开发任务 | 中大型项目 Claude Code 编排；多模型混合使用；AI 开发 Token 成本优化 | 2026-03-27 |
| last30days-skill | https://github.com/mvanhorn/last30days-skill | 多平台舆情调研需手动逐个搜索，效率低且难以全面覆盖 | 竞品情报收集；投资舆论监控；内容选题研究；Claude Code 原生技能 | 2026-03-27 |
| strix | https://github.com/usestrix/strix | 静态代码扫描误报率高，无法发现运行时动态漏洞 | DevSecOps CI/CD 安全集成；中小团队安全审计；AI 安全 Agent 研究参考 | 2026-03-27 |
| AgentScope | https://github.com/agentscope-ai/agentscope | 多 Agent 系统生产部署中可观测性缺失、调试困难 | 企业级多 Agent 系统、MCP/A2A 生态互通、语音 Agent | 2026-03-28 |
| AI-Scientist-v2 | https://github.com/SakanaAI/AI-Scientist-v2 | AI 无法自主完成从假设到同行评审的完整科研闭环 | ML 研究方向快速探索、自动化实验假设生成、agentic tree search 学习案例 | 2026-03-28 |
| SlopCodeBench（论文） | https://arxiv.org/abs/2603.24755 | 现有代码基准无法评估 AI 在多轮迭代中的代码质量退化 | AI 编程工具评估选型参考；迭代开发最佳实践指导；代码 Agent 训练数据优化 | 2026-03-28 |
| Intern-S1-Pro（论文） | https://arxiv.org/abs/2603.25040 | 开源模型在化学、材料、生命科学等专业领域性能严重不足 | 科学领域垂直 Agent；私有化科研智能问答；分子设计/材料发现工作流 | 2026-03-28 |
| Onyx | https://github.com/onyx-dot-app/onyx | 企业知识库与 LLM 整合门槛高，缺乏开箱即用的多源 RAG 平台 | 企业内部知识库问答；40+ 数据源连接；自定义 AI Agent 平台 | 2026-03-28 |
| daily_stock_analysis | https://github.com/ZhuLinsen/daily_stock_analysis | LLM 股票分析无法零成本、低门槛持续运行并推送结果 | 个人 A/H/美股自动分析；GitHub Actions 零成本定时运行；多 LLM 切换 | 2026-03-28 |
| obra/superpowers | https://github.com/obra/superpowers | 编码 Agent 缺乏系统化工程方法论，代码质量飘忽、无测试驱动、无任务规划 | Claude Code/Cursor/Codex/Gemini CLI 重度用户；中大型项目 AI 辅助开发；团队工程规范统一 | 2026-03-29 |
| learn-claude-code | https://github.com/shareAI-lab/learn-claude-code | 开发者不理解 Agent Harness 底层机制，无法掌控 AI 系统行为 | AI 工程师进阶学习；自研轻量级 Agent CLI/SDK；理解 Claude Code 核心机制 | 2026-03-29 |
| AVO（论文） | https://arxiv.org/abs/2603.24517 | GPU 算子极限优化依赖稀缺人类专家，无法规模化 | GPU 算子自动化优化；推理框架性能提升；新架构 GPU 软件栈快速适配 | 2026-03-29 |
| MSA（论文） | https://arxiv.org/abs/2603.23516 | LLM 有效上下文被限制在 1M Token 以内，无法实现真正的终身记忆 | 长期记忆 AI 助理；大规模语料库摘要；数字孪生；长历史 Agent 推理 | 2026-03-29 |
| VibeVoice | https://github.com/microsoft/VibeVoice | 长音频 ASR 无法同时输出说话人分离+时间戳+多语言转写 | 企业会议转录、播客字幕、医疗/法律专业录音；50+语言支持；实时 TTS | 2026-03-30 |
| claude-howto | https://github.com/luongnv89/claude-howto | 开发者不了解 Claude Code 完整功能体系，停留在基础使用层 | Claude Code 重度用户进阶；Agentic 工具链系统化学习；可视化模板复用 | 2026-03-30 |
| MiroFish | https://github.com/666ghj/MiroFish | 单一 AI 视角预测缺乏群体多样性，无法模拟复杂社会系统动态 | 政策推演、市场舆情预测、用户行为建模；多 Agent 研究；策略创作沙盒 | 2026-03-30 |
| K²-Agent（论文） | https://arxiv.org/abs/2603.00676 | GUI Agent 规划与执行耦合，移动设备长程任务成功率低 | Android 自动化测试；RPA 手机操控；少样本 Agent 训练框架参考 | 2026-03-30 |
| Draft-Thinking（论文） | https://arxiv.org/abs/2603.00578 | LLM 推理模型过度思考，Token 消耗冗余高达 70% | 推理模型成本优化；数学/代码推理高并发部署；推理效率微调框架参考 | 2026-03-30 |
| Trace2Skill（论文） | https://arxiv.org/abs/2603.25158 | Agent 无法从历史轨迹中自动提炼可迁移技能，经验无法积累 | Agent 技能库自动构建；跨模型技能迁移；企业 Agent 能力版本管理 | 2026-03-31 |
| Natural-Language Agent Harnesses（论文） | https://arxiv.org/abs/2603.25723 | Agent 控制逻辑深埋代码，无法跨框架移植、无法科学比较 | 多框架 Agent 迁移；可解释/可审计 AI 产品；非工程师参与 Agent 设计 | 2026-03-31 |
| agent-lightning | https://github.com/microsoft/agent-lightning | 现有 Agent 系统缺乏系统性自动优化机制，只能靠人工调 Prompt | 现有 Agent 系统性能提升；企业 AI 质量持续改进流水线；Agent RL 研究 | 2026-03-31 |
| ChatDev 2.0 | https://github.com/OpenBMB/ChatDev | 多 Agent 系统搭建门槛高，需要大量框架代码 | 零代码多 Agent 工作流；数据分析/调研自动化；可视化 Agent 编排 | 2026-03-31 |
| claude-code-best-practice | https://github.com/shanraisshan/claude-code-best-practice | Claude Code 功能强大但缺乏系统化最佳实践汇编，学习曲线陡 | Claude Code 重度用户进阶；Subagents/Skills/MCP 完整能力掌握；Agent 团队协作 | 2026-03-31 |
| AIRA₂（论文） | https://arxiv.org/abs/2603.26499 | AI 研究 Agent 存在吞吐量、评估噪声、算子能力三大结构性瓶颈 | AutoML 流水线；AI 研究自动化系统架构参考；异步多 GPU 超参搜索 | 2026-03-31 |
| Phantom | https://github.com/ghostwright/phantom | AI Agent 无持续存在、无独立工具积累、无法自主进化 | 需要 AI 持续担任数字员工的团队；企业自托管 AI 同事 | 2026-04-01 |
| wecom-cli | https://github.com/WecomTeam/wecom-cli | AI Agent 无法结构化操控企业微信，只能靠网页模拟 | 企业内部 AI 工作流自动化；AI 操作企业微信待办/会议/消息 | 2026-04-01 |
| llm-sast-scanner | https://github.com/SunWeb3Sec/llm-sast-scanner | AI 编程助手缺乏结构化安全扫描能力，漏洞意识弱 | AI+安全 DevSecOps；Claude Code/Codex 安全增强；Web3 安全审计 | 2026-04-01 |
| LongCat-Next（论文） | https://arxiv.org/abs/2603.27538 | 多模态理解与生成模型割裂，各模态浅层拼装 | 多模态产品设计；边缘端多模态部署；理解+生成统一模型选型 | 2026-04-01 |
| Think-Anywhere（论文） | https://arxiv.org/abs/2603.29957 | 前置推理无法覆盖代码生成过程中的动态复杂性 | 代码生成质量优化；推理模型效率改进；高并发代码补全 | 2026-04-01 |
| Khoj | https://github.com/khoj-ai/khoj | AI 助手缺乏持久记忆，无法基于用户文档和上下文持续服务 | 个人 AI 知识库；企业内网 RAG；多源文档检索；定时自动化任务 | 2026-04-01 |
| AgentFixer（论文） | https://arxiv.org/abs/2603.29848 | LLM Agent 生产环境缺乏系统性故障检测和根因分析 | Agent 系统可靠性验证；生产环境质量保障；AI QA 工具链 | 2026-04-01 |
| Hyperagents（论文） | https://arxiv.org/abs/2603.19461 | AI 只能改进"做什么"，无法改进"如何改进"，自我改进有天花板 | 元认知 AI 研究；开放式自我改进系统；AGI 方向探索 | 2026-04-01 |
| Drop the Hierarchy（论文） | https://arxiv.org/abs/2603.28990 | 多 Agent 系统预设角色和协调协议效率低，缺乏自组织能力 | 多 Agent 协作架构；自组织 AI 系统；大规模 AI 工作流 | 2026-04-01 |
