# 文档索引

本目录收纳项目的规划、需求、路线图与阶段文档。

如果你是第一次访问这个仓库，请先阅读根目录的 [README.md](../README.md)。根 README 用来说明项目定位、当前首页内容和主要项目入口；这里则只负责文档导航。

## 核心文档

- [PROJECT.md](PROJECT.md) — 项目定义、核心价值、范围约束与关键决策
- [REQUIREMENTS.md](REQUIREMENTS.md) — v1 / v2 需求规格与追溯关系
- [ROADMAP.md](ROADMAP.md) — 三阶段开发路线图与阶段目标

## 阶段文档

`phases/` 目录按阶段保存上下文、讨论记录与设计约束：

- [phases/01-positioning-homepage-skeleton/01-CONTEXT.md](phases/01-positioning-homepage-skeleton/01-CONTEXT.md) — Phase 1 的范围、决策与代码上下文
- [phases/01-positioning-homepage-skeleton/01-DISCUSSION-LOG.md](phases/01-positioning-homepage-skeleton/01-DISCUSSION-LOG.md) — Phase 1 讨论备忘与取舍记录
- [phases/01-positioning-homepage-skeleton/01-UI-SPEC.md](phases/01-positioning-homepage-skeleton/01-UI-SPEC.md) — Phase 1 页面结构、排版、颜色与交互约束

后续阶段文档会继续按同样结构补充在 `phases/` 下。

## 使用建议

- 想快速理解项目是什么：先看 [../README.md](../README.md)
- 想理解为什么这样做：看 [PROJECT.md](PROJECT.md)
- 想确认当前做什么、不做什么：看 [REQUIREMENTS.md](REQUIREMENTS.md)
- 想了解接下来怎么推进：看 [ROADMAP.md](ROADMAP.md)
- 想回溯某个阶段的决策依据：看 `phases/` 下对应阶段文档

## 说明

本地执行状态和临时 planning 工件可能存在于未纳入版本控制的 `.planning/` 目录中；`docs/` 只保留需要随仓库共享的稳定文档。