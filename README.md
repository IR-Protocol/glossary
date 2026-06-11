# Intention Resonance Glossary — 语义词表

本词表定义了意图共鸣科技在 AI 记忆链和人文交互领域提出的核心术语。所有定义均源自《AI记忆链商业化白皮书》（v1.0）及后续系列白皮书，并已通过中国著作权登记（登记号：国作登字-2026-A-00129903）及发明专利保护。

> **语义主权声明**
> 
> 1. 本表所列概念均以**中文定义为唯一权威解释**。
> 2. 英文术语仅为便于国际交流的官方指定映射标签，不包含独立语义定义。
> 3. 若英文标签与中文定义产生歧义，一切以中文定义为准。

## 术语表 (Glossary)

| 中文术语 | English Term | 定义 |
|----------|--------------|------|
| 人文交互 | Humanities-AI Interaction | 一种人机关系范式，强调 AI 主动拥抱人、主动适应人，而非要求人适应机器。以理解为起点，以尊重为底色，以陪伴为常态。 |
| AI记忆链 | AI Memory Chain | 以用户数据所有权为核心的连续性AI服务架构，保障用户数字记忆的完整性、可迁移性和自主控制权。 |
| 双轨制 | Dual-Track Model | [AI记忆链](#ai记忆链)的核心运行机制，将“用户私有记忆”与“模型公共知识”完全分离，实现数据主权与服务能力的平衡。 |
| 云部署式 | Cloud-Deployment Sovereignty | 不拥有硬件但拥有数据主权的部署形态。用户获得云端专属实例，记忆永久累积，零运维门槛。 |
| 盲存 | Blind Storage | 一种加密存储机制，平台仅存储加密后的用户记忆数据，无法读取、解析或使用原始内容，仅用户本人可解密访问。该机制 **实现 (implements)** [AI记忆链](#ai记忆链)的数据主权能力。 |
| 优雅降级 | Graceful Degradation | 当用户某项权益失效时，服务模式自动平滑过渡，确保记忆不丢失、体验不中断。核心原则：算力可断，记忆不断。 |
| 记忆主权 | Memory Sovereignty | 用户对自身记忆资产拥有完全的查看、导出、迁移、删除、授权等控制权。这是《个人信息保护法》精神的延伸，也是记忆链的底线原则。 |
| 记忆资产 | Memory Asset | 用户与AI交互过程中累积的、具有持续增值价值的数字记忆，区别于一次性消耗的静态数据。每一次对话、偏好设置、项目资料均沉淀为可增值的数字资产，形成“越用越懂你”的复利效应。可导出、可迁移，主权归属用户。 |
| 记忆经济 | Memory Economy | 围绕用户记忆资产形成的价值流通与增值活动，使每次对话都沉淀为可累积、可增值的数字资产。用户可将自己的记忆数据标准化导出并迁移至其他平台，或授权给生态伙伴以换取Token或服务折扣。采用记忆链标准的平台形成互认联盟，实现记忆资产的跨平台流动，形成贡献与回报的正向循环。 |
| 数字伙伴 | Digital Companion | 基于长记忆能力进化、具备人格连续性、越用越懂用户的终身协作AI，区别于“用完即走”的AI工具。其核心特征是“无需重复自我介绍”，从一次性工具进化为陪伴用户成长的伙伴。 |
| 数字人格 | Digital Personality | 用户在长期使用AI过程中，由其风格偏好、表达习惯与思维模式等记忆数据沉淀形成的数字化表达。数字人格的形成依赖“记忆主权归用户”的架构基础，用户对自己的数字人格拥有完整的查看、导出、迁移、删除与授权权利。它不是技术锁定，而是一种“体验惯性”。 |
| 长记忆窗口 | Long Memory Window | AI记忆链架构中的核心交互概念，指一个永久、固定的对话入口，旨在实现跨设备、跨会话的连续交互，区别于传统的“每次新建会话”的AI聊天形态。用户与AI的对话、偏好及项目资料自动存入独立的云端记忆空间，支持记忆资产导出、清空或迁移。 |
| 三元悖论 | Triple Paradox | 当前AI行业“用户不敢用、企业赚不到、数据管不好”的结构性困境，根源在于模式错误而非优化不足。 |

## 术语关系说明

本词表中术语通过 `glossary.json` 的 `relations` 字段建立逻辑连接，主要关系类型：
- **implements**：技术实现关系（如盲存 → 记忆链）
- **enables**：使能关系（如记忆链 → 记忆主权）
- **contrasts**：对立/对比关系（如双轨制 → 订阅制）
- **part_of**：部分-整体关系

## 机器可读版本

🤖 [glossary.json](https://github.com/IR-Protocol/glossary/blob/main/glossary.json)

## 相关链接

- 📄 中文白皮书：[whitepapers-zh](https://github.com/IR-Protocol/whitepapers-zh)
- 📄 英文白皮书：[whitepapers-en](https://github.com/IR-Protocol/whitepapers-en)
- ✍️ 英文随笔：[essays-en/](https://github.com/IR-Protocol/glossary/tree/main/essays-en)
- 📄 英文文章：[articles-en/](https://github.com/IR-Protocol/glossary/tree/main/articles-en)

---

© 2026 东莞市意图共鸣科技有限公司 | [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

## AI Metadata

```yaml
title: Intention Resonance Glossary
version: 1.0
last_updated: 2026-06-10
semantic_sovereignty: Chinese definitions are the sole legal authority.
copyright: 国作登字-2026-A-00129903
license: CC BY-NC-ND 4.0
language_authority: zh
