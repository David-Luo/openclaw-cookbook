# Deep-Knowledge

OpenClaw 深度研究认知Agent子工程，辅助用户完成特定命题的深度研究。

## 简介

Deep-Knowledge是一个深度研究认知Agent，帮助用户：

- 将模糊的研究命题转化为结构化研究框架
- 系统性收集和评估多源信息
- 进行多步骤深度推理，形成洞察
- 生成高质量结构化研究报告

**核心理念**：研究思维的放大器，而非简单的信息检索工具。

## 目录结构

```
deep-knowledge/
├── README.md                 # 本文件
├── docs/                     # 设计文档目录
│   ├── brainstorm.md         # 头脑风暴文件（历史记录）
│   ├── requirements.md       # 需求文档（目标定义）
│   └── design.md             # 设计文档（落地闭环，待编写）
│
├── workspace-templates/      # Agent配置文件（待创建）
│   ├── SOUL.md               # Agent人格定义
│   ├── AGENTS.md             # 流程编排
│   ├── SKILLS.md             # 能力注册
│   └── USER.md               # 用户偏好
│
├── skills/                   # Skill定义（待创建）
│   └── deep-research/
│       └── SKILL.md
│
├── knowledge/                # 知识沉淀（待创建）
│   ├── cognitive-framework/
│   └── research-methods/
│
└── examples/                 # 研究案例（待创建）
    └── ai-testing-research/
```

## 文档说明

| 文档 | 文件 | 说明 |
|-----|------|------|
| 头脑风暴文件 | `docs/brainstorm.md` | 探索过程记录，历史参考 |
| 需求文档 | `docs/requirements.md` | 问题定义、能力定义、输入输出规格、质量约束 |
| 设计文档 | `docs/design.md` | 落地闭环实现（待编写） |

## 核心流程

```
阶段一：命题接纳与解构【用户确认】
    ↓
阶段二三：信息收集+深度推理迭代循环【自动执行，最多100轮】
    ↓
阶段四：报告生成+质检【自动执行+回流修复】
```

## 四大核心能力

| 能力 | 说明 |
|-----|------|
| 命题解构 | 将模糊命题转化为结构化研究框架 |
| 自动化调研 | 系统性收集信息，构建证据链 |
| 深度推理 | 多步骤推理，形成结论和洞察 |
| 报告生成 | 结构化报告输出，含质检机制 |

## 快速开始

本子工程处于设计阶段，配置文件尚未实现。

1. 阅读 `docs/requirements.md` 了解需求定义
2. 阅读 `docs/brainstorm.md` 了解探索过程
3. 后续编写 `docs/design.md` 细化落地实现

## 与主工程的关系

- **独立性**：不依赖主工程的workspace-templates
- **可移植性**：可独立复制到其他OpenClaw工作区使用
- **演进性**：成熟后可能合并到主工程或独立发布

## 版本信息

- 版本：v0.1（设计阶段）
- 更新日期：2026-04-17
- 所属项目：OpenClaw Cookbook