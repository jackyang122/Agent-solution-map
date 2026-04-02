# AI Agent 全局解决方案映射表

> 按天累积，自动追加 | [查看完整列表](#全部项目索引)

## 快速导航

| 分类 | 项目 |
|------|------|
| [记忆与知识管理](#记忆与知识管理) | MuSEAgent, Khoj, Supermemory, Hermes-Agent, MSA |
| [多Agent协作](#多agent协作) | AgentScope, ChatDev 2.0, Drop the Hierarchy, MiroFish |
| [Agent开发框架](#agent开发框架) | LangGraph, Deer-Flow, DeerFlow 2.0, oh-my-claudecode |
| [AI安全与测试](#ai安全与测试) | Beyond pass@1, AgentFixer, llm-sast-scanner, strix, SlopCodeBench |
| [推理与优化](#推理与优化) | Draft-Thinking, Think-Anywhere, AVO, Nemotron-Cascade 2 |
| [多模态](#多模态) | EVA, LongCat-Next, SpecEyes, LTX-2, ATP-Bench, AEC-Bench |
| [GUI与自动化](#gui与自动化) | UI-Voyager, K²-Agent, browser-use, wecom-cli |
| [研究与科学](#研究与科学) | AI-Scientist-v2, Hyperagents, EvoScientist, Intern-S1-Pro |
| [编程工具](#编程工具) | everything-claude-code, claude-howto, claude-code-best-practice, learn-claude-code |
| [金融与量化](#金融与量化) | OpenBB, TradingAgents, dexter, daily_stock_analysis |
| [其他工具](#其他工具) | CausalPulse, Phantom, VibeVoice, Onyx, agent-lightning, PAR²-RAG, mem0 |

---

## 记忆与知识管理

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| MuSEAgent（论文） | [arXiv](https://arxiv.org/abs/2603.27813) | 多模态Agent缺乏状态化经验复用能力 | 多模态推理；视觉感知 | 2026-04-01 |
| Khoj | [GitHub](https://github.com/khoj-ai/khoj) | AI助手缺乏持久记忆 | 个人AI知识库；企业内网RAG | 2026-04-01 |
| Supermemory | [GitHub](https://github.com/supermemoryai/supermemory) | RAG无状态，无法追踪用户变化 | 多用户AI产品记忆API | 2026-03-26 |
| Hermes-Agent | [GitHub](https://github.com/NousResearch/Hermes-Agent) | 跨会话失忆，无法积累偏好 | 长期记忆个人AI助手 | 2026-03-26 |
| MSA（论文） | [arXiv](https://arxiv.org/abs/2603.23516) | 上下文被限制在1M Token内 | 长期记忆AI助理 | 2026-03-29 |

## 多Agent协作

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| Drop the Hierarchy | [arXiv](https://arxiv.org/abs/2603.28990) | 预设角色效率低，缺乏自组织 | 多Agent协作架构 | 2026-04-01 |
| AgentScope | [GitHub](https://github.com/agentscope-ai/agentscope) | 生产部署可观测性缺失 | 企业级多Agent系统 | 2026-03-28 |
| ChatDev 2.0 | [GitHub](https://github.com/OpenBMB/ChatDev) | 多Agent搭建门槛高 | 零代码多Agent工作流 | 2026-03-31 |
| MiroFish | [GitHub](https://github.com/666ghj/MiroFish) | 单一AI视角缺乏群体多样性 | 政策推演；舆情预测 | 2026-03-30 |

## Agent开发框架

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| LangGraph | [官网](https://langchain-ai.github.io/langgraph/) | Agent逻辑无法支持循环/分支 | 多Agent编排框架 | 2026-03-24 |
| Deer-Flow | [GitHub](https://github.com/bytedance/deer-flow) | 单Agent无法完成复杂多步骤任务 | 竞品调研自动化 | 2026-03-24 |
| DeerFlow 2.0 | [GitHub](https://github.com/bytedance/deer-flow) | 上下文溢出，无法小时级执行 | 深度研究报告生成 | 2026-03-25 |
| oh-my-claudecode | [GitHub](https://github.com/Yeachan-Heo/oh-my-claudecode) | 单Agent无法多角色协同 | 中大型项目Claude编排 | 2026-03-27 |

## AI安全与测试

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| Beyond pass@1（论文） | [arXiv](https://arxiv.org/abs/2603.29231) | pass@1无法衡量Agent长周期可靠性 | Agent可靠性评估；生产部署 | 2026-04-01 |
| AgentFixer | [arXiv](https://arxiv.org/abs/2603.29848) | Agent缺乏系统性故障检测 | 生产环境质量保障 | 2026-04-01 |
| llm-sast-scanner | [GitHub](https://github.com/SunWeb3Sec/llm-sast-scanner) | AI编程缺乏安全扫描能力 | AI+安全DevSecOps | 2026-04-01 |
| strix | [GitHub](https://github.com/usestrix/strix) | 静态扫描误报率高 | DevSecOps CI/CD | 2026-03-27 |
| SlopCodeBench | [arXiv](https://arxiv.org/abs/2603.24755) | 无法评估AI代码质量退化 | AI编程工具评估 | 2026-03-28 |

## 推理与优化

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| Draft-Thinking | [arXiv](https://arxiv.org/abs/2603.00578) | 推理模型过度思考，Token浪费70% | 推理成本优化 | 2026-03-30 |
| Think-Anywhere | [arXiv](https://arxiv.org/abs/2603.29957) | 前置推理无法覆盖动态复杂性 | 代码生成质量优化 | 2026-04-01 |
| AVO（论文） | [arXiv](https://arxiv.org/abs/2603.24517) | GPU算子优化依赖人类专家 | GPU算子自动化优化 | 2026-03-29 |
| Nemotron-Cascade 2 | [arXiv](https://arxiv.org/abs/2603.19220) | 多任务RL灾难性遗忘 | 低成本高性能推理 | 2026-03-25 |

## 多模态

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| EVA（论文） | [arXiv](https://arxiv.org/abs/2603.22918) | 长视频Token爆炸，效率低 | 长视频问答；视频RAG | 2026-03-27 |
| LongCat-Next | [arXiv](https://arxiv.org/abs/2603.27538) | 多模态理解与生成模型割裂 | 多模态产品设计 | 2026-04-01 |
| SpecEyes | [arXiv](https://arxiv.org/abs/2603.23483) | 工具调用链串行延迟高 | MLLM推理加速 | 2026-03-26 |
| LTX-2 | [GitHub](https://github.com/Lightricks/LTX-2) | 音视频生成不同步 | 音视频联合生成 | 2026-01-07 |
| ATP-Bench（论文） | [arXiv](https://arxiv.org/abs/2603.29902) | MLLM缺乏工具规划能力评估标准 | 多模态Agent工具调度；MLLM评测 | 2026-04-02 |
| AEC-Bench（论文） | [arXiv](https://arxiv.org/abs/2603.29199) | 建筑工程领域缺乏多模态Agent基准 | 建筑/工程/施工AI应用 | 2026-04-02 |

## GUI与自动化

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| UI-Voyager | [arXiv](https://arxiv.org/abs/2603.24533) | GUI Agent无法从失败中学习 | Android自动化测试 | 2026-03-27 |
| K²-Agent | [arXiv](https://arxiv.org/abs/2603.00676) | 规划与执行耦合，成功率低 | RPA手机操控 | 2026-03-30 |
| browser-use | [GitHub](https://github.com/browser-use/browser-use) | AI无法操控真实浏览器 | 网页数据抓取 | 2026-03-24 |
| wecom-cli | [GitHub](https://github.com/WecomTeam/wecom-cli) | AI无法结构化操控企业微信 | 企业内部AI工作流 | 2026-04-01 |

## 研究与科学

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| Hyperagents | [arXiv](https://arxiv.org/abs/2603.19461) | AI无法改进"如何改进"本身 | 元认知AI研究；AGI | 2026-04-01 |
| AI-Scientist-v2 | [GitHub](https://github.com/SakanaAI/AI-Scientist-v2) | AI无法完成完整科研闭环 | ML研究方向探索 | 2026-03-28 |
| EvoScientist | [GitHub](https://github.com/EvoScientist/EvoScientist) | 多Agent缺乏持续学习能力 | 端到端科学发现 | 2026-03-09 |
| Intern-S1-Pro | [arXiv](https://arxiv.org/abs/2603.25040) | 开源模型专业领域性能不足 | 科学领域垂直Agent | 2026-03-28 |

## 编程工具

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| everything-claude-code | [GitHub](https://github.com/AFFAAN-M/everything-claude-code) | 跨会话失忆，无安全边界 | 企业级AI编程管控 | 2026-03-24 |
| claude-howto | [GitHub](https://github.com/luongnv89/claude-howto) | 开发者不了解完整功能体系 | Claude Code进阶 | 2026-03-30 |
| claude-code-best-practice | [GitHub](https://github.com/shanraisshan/claude-code-best-practice) | 缺乏系统化最佳实践 | Agent团队协作 | 2026-03-31 |
| learn-claude-code | [GitHub](https://github.com/shareAI-lab/learn-claude-code) | 不理解Harness底层机制 | AI工程师进阶学习 | 2026-03-29 |

## 金融与量化

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| OpenBB | [GitHub](https://github.com/OpenBB-finance/OpenBB) | 金融数据源分散，AI Agent接入门槛高 | 量化分析；AI金融Agent数据层 | 2026-04-01 |
| TradingAgents | [GitHub](https://github.com/TauricResearch/TradingAgents) | 单一模型缺乏多角度博弈验证 | 量化策略研究 | 2026-03-24 |
| dexter | [GitHub](https://github.com/virattt/dexter) | AI金融分析无自我验证 | 基本面财报分析 | 2026-03-27 |
| daily_stock_analysis | [GitHub](https://github.com/ZhuLinsen/daily_stock_analysis) | LLM股票分析无法持续运行 | 个人A/H/美股分析 | 2026-03-28 |

## 其他工具

| 项目 | 链接 | 核心问题 | 适用场景 | 日期 |
|------|------|----------|----------|------|
| CausalPulse（论文） | [arXiv](https://arxiv.org/abs/2603.29755) | 制造业根因分析流程割裂，无法实时诊断 | 智能制造；工业级多Agent | 2026-04-01 |
| Phantom | [GitHub](https://github.com/ghostwright/phantom) | Agent无持续存在，无法自主进化 | 企业自托管AI同事 | 2026-04-01 |
| VibeVoice | [GitHub](https://github.com/microsoft/VibeVoice) | 长音频无法同时输出说话人分离 | 企业会议转录 | 2026-03-30 |
| Onyx | [GitHub](https://github.com/onyx-dot-app/onyx) | 企业知识库整合门槛高 | 企业内部知识库问答 | 2026-03-28 |
| agent-lightning | [GitHub](https://github.com/microsoft/agent-lightning) | Agent缺乏自动优化机制 | 企业AI质量改进流水线 | 2026-03-31 |
| MetaClaw | [GitHub](https://github.com/aiming-lab/MetaClaw) | Agent无法从真实对话中进化 | SaaS产品自进化Agent | 2026-03-25 |
| OpenResearcher | [GitHub](https://github.com/TIGER-AI-Lab/OpenResearcher) | 深度研究依赖昂贵外部API | 金融/医疗私有化研究 | 2026-03-25 |
| Trace2Skill | [arXiv](https://arxiv.org/abs/2603.25158) | Agent无法自动提炼可迁移技能 | Agent技能库构建 | 2026-03-31 |
| Natural-Language Agent Harnesses | [arXiv](https://arxiv.org/abs/2603.25723) | Agent控制逻辑无法跨框架移植 | 多框架Agent迁移 | 2026-03-31 |
| AIRA₂ | [arXiv](https://arxiv.org/abs/2603.26499) | AI研究Agent存在三大瓶颈 | AutoML流水线 | 2026-03-31 |
| LongCat-Flash-Prover | [arXiv](https://arxiv.org/abs/2603.21065) | LLM无法完成Lean4形式化证明 | 代码形式化验证 | 2026-03-26 |
| last30days-skill | [GitHub](https://github.com/mvanhorn/last30days-skill) | 多平台舆情调研效率低 | 竞品情报收集 | 2026-03-27 |
| obra/superpowers | [GitHub](https://github.com/obra/superpowers) | 编码Agent缺乏工程方法论 | 团队工程规范统一 | 2026-03-29 |
| PAR²-RAG（论文） | [arXiv](https://arxiv.org/abs/2603.29085) | 多跳问答中早期检索错误累积导致答案失准 | 复杂问答RAG；Agent知识检索 | 2026-04-02 |
| mem0 | [GitHub](https://github.com/mem0ai/mem0) | AI应用缺乏跨会话持久化记忆层 | 个性化AI助手；Agent记忆管理 | 2026-04-02 |

---

## 全部项目索引

<details>
<summary>点击展开完整列表（57个项目）</summary>

| # | 项目名称 | 收录日期 |
|---|----------|----------|
| 1 | Deer-Flow | 2026-03-24 |
| 2 | browser-use | 2026-03-24 |
| 3 | TradingAgents | 2026-03-24 |
| 4 | everything-claude-code | 2026-03-24 |
| 5 | LangGraph | 2026-03-24 |
| 6 | MetaClaw | 2026-03-25 |
| 7 | DeerFlow 2.0 | 2026-03-25 |
| 8 | Nemotron-Cascade 2 | 2026-03-25 |
| 9 | OpenResearcher | 2026-03-25 |
| 10 | Hermes-Agent | 2026-03-26 |
| 11 | Supermemory | 2026-03-26 |
| 12 | SpecEyes | 2026-03-26 |
| 13 | LongCat-Flash-Prover | 2026-03-26 |
| 14 | UI-Voyager | 2026-03-27 |
| 15 | EVA | 2026-03-27 |
| 16 | dexter | 2026-03-27 |
| 17 | oh-my-claudecode | 2026-03-27 |
| 18 | last30days-skill | 2026-03-27 |
| 19 | strix | 2026-03-27 |
| 20 | AgentScope | 2026-03-28 |
| 21 | AI-Scientist-v2 | 2026-03-28 |
| 22 | SlopCodeBench | 2026-03-28 |
| 23 | Intern-S1-Pro | 2026-03-28 |
| 24 | Onyx | 2026-03-28 |
| 25 | daily_stock_analysis | 2026-03-28 |
| 26 | obra/superpowers | 2026-03-29 |
| 27 | learn-claude-code | 2026-03-29 |
| 28 | AVO | 2026-03-29 |
| 29 | MSA | 2026-03-29 |
| 30 | VibeVoice | 2026-03-30 |
| 31 | claude-howto | 2026-03-30 |
| 32 | MiroFish | 2026-03-30 |
| 33 | K²-Agent | 2026-03-30 |
| 34 | Draft-Thinking | 2026-03-30 |
| 35 | Trace2Skill | 2026-03-31 |
| 36 | Natural-Language Agent Harnesses | 2026-03-31 |
| 37 | agent-lightning | 2026-03-31 |
| 38 | ChatDev 2.0 | 2026-03-31 |
| 39 | claude-code-best-practice | 2026-03-31 |
| 40 | AIRA₂ | 2026-03-31 |
| 41 | Phantom | 2026-04-01 |
| 42 | wecom-cli | 2026-04-01 |
| 43 | llm-sast-scanner | 2026-04-01 |
| 44 | LongCat-Next | 2026-04-01 |
| 45 | Think-Anywhere | 2026-04-01 |
| 46 | Khoj | 2026-04-01 |
| 47 | AgentFixer | 2026-04-01 |
| 48 | Hyperagents | 2026-04-01 |
| 49 | Drop the Hierarchy | 2026-04-01 |
| 50 | MuSEAgent | 2026-04-01 |
| 51 | Beyond pass@1 | 2026-04-01 |
| 52 | OpenBB | 2026-04-01 |
| 53 | CausalPulse | 2026-04-01 |
| 54 | ATP-Bench | 2026-04-02 |
| 55 | AEC-Bench | 2026-04-02 |
| 56 | PAR²-RAG | 2026-04-02 |
| 57 | mem0 | 2026-04-02 |

</details>

---

*本项目由 AI 自动维护，每日 8:30 更新 | [提交Issue/PR](https://github.com/jackyang122/Agent-solution-map/issues)*
