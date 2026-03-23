# references/ — 外部资源索引

相关文章、仓库、工具的统一索引。这里是指针，不是内容本身。

## 文件约定

- 按主题分文件，如 `articles.md`、`repos.md`、`tools.md`
- 每条记录包含：链接、一句话说明、与 Harness Engineering 的关联

## 核心参考

### 原始来源

| 资源 | 说明 |
|------|------|
| [OpenAI 原文（中文）](https://openai.com/zh-Hans-CN/index/harness-engineering/) | Harness Engineering 的完整阐述，2026-02-11 |

### Ralph 系列

| 项目 | Stars | 说明 | 关联概念 |
|------|-------|------|---------|
| [snarktank/ralph](https://github.com/snarktank/ralph) | 13.6k | 原版 Ralph 循环：bash + PRD + 每次清空上下文 | 全部六大概念的最小实现 |
| [ralph-orchestrator](https://mikeyobrien.github.io/ralph-orchestrator/) | 2.3k | Rust 版：Hat 角色 + 事件驱动 + 背压 | 机械化执行、熵管理 |
| [bmad-ralph](https://github.com/qianxiaofeng/bmad-ralph) | 2 | BMAD + Ralph：并行 worktree + 三层自愈 | 自主水平提升、吞吐量 |

### 社区指南

| 资源 | 说明 | 关联 |
|------|------|------|
| [vibe-coding-cn](https://github.com/tukuaiai/vibe-coding-cn) | 中文 Vibe Coding 社区，419 commits | 仓库组织方式、AGENTS.md 分级 |

### 待补充

- [ ] Geoffrey Huntley 的 Ralph 原始文章
- [ ] OpenAI 相关文章：Codex App Server、Responses API
- [ ] 其他 Harness Engineering 实践案例
