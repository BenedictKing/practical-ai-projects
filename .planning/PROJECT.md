# My Best Practice

## What This Is

这是一个围绕我已开发项目的统一展示主页，用来向开源访客、潜在客户和招聘方清楚说明我做过什么，以及我如何解决 AI 使用中的实际阻碍。网站 v1 采用单页主页结构，重点不是视觉炫技，而是用清晰的信息架构承载项目展示；GitHub README 则作为主页内容的精简版，帮助访客在仓库中直接看到主要内容。

## Core Value

用清晰、可信、可快速浏览的方式，让访客理解我如何通过具体项目解决普通用户在使用 AI 时遇到的真实问题。

## Requirements

### Validated

(None yet — ship to validate)

### Active

- [ ] 提供一个统一的单页展示主页框架，能够承载个人定位、AI 使用痛点、项目展示与导航入口
- [ ] 建立与主页内容同源的 README 展示框架，让 GitHub 访客也能快速理解核心内容
- [ ] 用项目卡片/区块清晰表达每个项目的面向对象、解决的痛点，以及 GitHub 或在线访问入口

### Out of Scope

- 后台或管理面板 — v1 重点是对外展示，不需要内容管理系统
- 登录、评论或互动系统 — 当前目标是信息传达与项目浏览，不是社区互动
- 自动从仓库抓取项目数据 — 先建立清晰的展示框架，后续再考虑自动化同步
- 复杂视觉动效或炫技式设计 — 当前优先级是表达清楚定位与项目价值，而不是精美视觉

## Context

用户希望把自己开发过的一些项目整合到一个展示主页中，并且这些项目会围绕“普通用户使用 AI 的真实痛点”来组织和呈现。当前阶段先做整体设计与统一框架，不急于锁定具体项目内容；后续会随着实际项目加入，再细化内容组织方式。

目标受众包含三类：开源访客、潜在客户、招聘方。三类受众的共同需求是快速理解“你做了什么、解决了什么问题、项目入口在哪里”；其中当前最重要的转化动作是让访客继续查看具体项目。

项目展示的最小信息集已经明确：每个项目至少需要说明面向谁、解决了什么痛点，以及 GitHub/在线地址。README 不是独立文档，而是主页内容的精简版，因此后续实现应优先考虑内容同源，减少重复维护。

## Constraints

- **Scope**: v1 只做单页主页与 README 框架 — 先验证表达与结构是否清晰
- **Content Strategy**: 主页与 README 内容同源 — 避免维护两套割裂内容
- **UX Priority**: 主要引导访客进入具体项目 — 首页应更像清晰的入口与定位说明
- **Design**: 不追求复杂视觉与动效 — 优先保证信息层次、可读性与可信度

## Key Decisions

| Decision | Rationale | Outcome |
|----------|-----------|---------|
| v1 采用单页主页 | 当前先建立统一展示框架，降低实现复杂度并加快形成可用版本 | — Pending |
| README 作为主页内容精简版 | GitHub 访客需要在仓库内直接看到核心信息，同时避免重复写两份内容 | — Pending |
| 项目展示先围绕 AI 使用实际阻碍展开 | 这是整个展示站的核心差异化定位，也是后续选择和组织项目的主线 | — Pending |
| v1 不做后台、互动系统和自动抓取 | 当前阶段重点是表达清楚定位与项目价值，而不是扩展系统能力 | — Pending |

## Evolution

This document evolves at phase transitions and milestone boundaries.

**After each phase transition** (via `/gsd-transition`):
1. Requirements invalidated? → Move to Out of Scope with reason
2. Requirements validated? → Move to Validated with phase reference
3. New requirements emerged? → Add to Active
4. Decisions to log? → Add to Key Decisions
5. "What This Is" still accurate? → Update if drifted

**After each milestone** (via `/gsd-complete-milestone`):
1. Full review of all sections
2. Core Value check — still the right priority?
3. Audit Out of Scope — reasons still valid?
4. Update Context with current state

---
*Last updated: 2026-04-17 after initialization*
