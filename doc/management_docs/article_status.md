# Article Status

This file is an internal working table for tracking article production status.
It is intended for Codex-assisted planning and follow-up, not for public publishing.

## Status Legend

| Status | Meaning |
|---|---|
| published | Article has been published or archived as final output |
| draft_done | Main draft is complete, pending polish or publishing work |
| writing | Article is actively being written |
| planned | Topic is planned but not started |
| paused | Topic is temporarily parked |
| review_needed | Needs structure, argument, or boundary review before continuing |

## Season 1 Article Tracker

| No. | Current Title | Line | Object / Issue | AI Depth | Status | Local Folder | Next Action | Notes |
|---|---|---|---|---|---|---|---|---|
| 01 | 为什么越成熟的 SAP 乙方团队，越需要 AI？ | positioning | 总定位 | 第一层 / 第二层 / 第三层 | published | `doc/column_content/01_SAP维护作业AI增强拆解/01_为什么越成熟的SAP乙方团队越需要AI` | Track reuse and follow-up ideas | Existing article and assets have been organized |
| 02 | Incident 处理里，AI 第一步不是自动解单，而是把工单入口变完整 | scenario | Incident 入口 | 第一层 | planned |  | Write outline and first draft | Use this as the first concrete scenario sample |
| 03 | 成熟 SAP 乙方团队上 AI 前，会先问什么？ | governance | 企业 AI 落地边界 | 第一层 / 第二层 / 第三层 | planned |  | Write governance overview | Should introduce the mature-team question matrix |
| 04 | Problem / RCA 不是写报告，而是把重复问题纳入治理 | scenario | Problem / RCA | 第一层 / 第二层 | planned |  | Write outline | Connect RCA, Known Error, recurrence governance |
| 05 | 历史工单分类不准，AI 怎么学？ | governance | 数据质量 / 标签治理 | 第二层 | planned |  | Write outline | Focus on labels, taxonomy, sampling, human review |
| 06 | 定常任务里，AI 真正有价值的是前后值记录和验证证据 | scenario | 定常任务 / 月度主数据维护 | 第一层 | planned |  | Build from existing material library | Use monthly master data maintenance as concrete case |
| 07 | AI 输出不稳定，审核成本怎么算？ | governance | 审核成本 / 试点验证 | 第一层 / 第二层 | planned |  | Write outline | Discuss adoption rate, review time, rework reduction |
| 08 | Service Request 为什么最适合先做 AI 补料和审批材料检查？ | scenario | Service Request | 第一层 | planned |  | Write outline | Include permissions, master data, standard requests |
| 09 | 客户不让历史工单出系统，AI 还能怎么试点？ | governance | 数据边界 / 脱敏 / 离线验证 | 第一层 | planned |  | Write outline | Focus on anonymized samples, simulated tickets, allowed environments |
| 10 | Change / Enhancement 里，AI 最该先检查的不是方案，而是影响范围和回退条件 | scenario | Change / Enhancement | 第一层 / 第二层 | planned |  | Write outline | Keep boundary clear: no auto approval, no auto release |
| 11 | L2/L3 深度集成前，权限、安全、审计、脱敏要先想清楚什么？ | governance | 深度集成治理 | 第三层 | planned |  | Write outline | Explain why deeper integration requires stricter controls |
| 12 | 月报不是堆数字，AI 能帮 AMS 经理看到哪些服务治理信号？ | scenario | 月报 / SLA / 服务治理 | 第二层 | planned |  | Write outline | Connect prior article outputs into management insight |

## Update Rules

- Update `Status` whenever an article moves between planned, writing, draft_done, published, paused, or review_needed.
- Fill `Local Folder` only after the article folder exists.
- Keep tactical publishing details here, not in the mother document.
- Do not use this file as public-facing copy.
