<!-- Parent: ../AGENTS.md -->
<!-- Generated: 2026-05-15 | Updated: 2026-05-15 -->

# DDIA 第二版 · 精读笔记

## Purpose
《Designing Data-Intensive Applications》（数据密集型应用系统设计）第二版（Martin Kleppmann 著）的完整精读笔记。包含全部 14 章的章节笔记、精读笔记（基于 Adler 分析阅读法）、原书插图及每章思维导图。中文翻译来源于 [Vonng/ddia](https://github.com/Vonng/ddia)。

## Key Files

| File | Description |
|------|-------------|
| `_index.md` | 书籍入口页 — 元数据、阅读进度清单、章节导航、核心概念速查表 |
| `目录.md` | 全书完整目录（含小节），带 Wiki 链接 |
| `前言.md` | 原书前言笔记 |
| `术语表.md` | 全书术语整理 |
| `出版后记.md` | 中文版出版后记 |
| `第一部分-数据系统基础.md` | 第一部分综述（第1-5章） |
| `第二部分-分布式数据.md` | 第二部分综述（第6-10章） |
| `第三部分-衍生数据.md` | 第三部分综述（第11-14章） |

### 章节笔记（共 14 章）

| File | 章节 | 精读状态 |
|------|------|----------|
| `第1章-数据系统架构中的权衡.md` | 数据系统架构中的权衡 | ✅ 已完成 |
| `第1章-精读笔记.md` | 第1章 Adler 分析阅读笔记 | ✅ 已完成 |
| `第2章-定义非功能性需求.md` | 定义非功能性需求 | ✅ 已完成 |
| `第2章-精读笔记.md` | 第2章 Adler 分析阅读笔记 | ✅ 已完成 |
| `第3章-数据模型与查询语言.md` | 数据模型与查询语言 | ⏳ 待阅读 |
| `第4章-存储与检索.md` | 存储与检索 | ⏳ 待阅读 |
| `第5章-编码与演化.md` | 编码与演化 | ⏳ 待阅读 |
| `第6章-复制.md` | 复制 | ⏳ 待阅读 |
| `第7章-分片.md` | 分片 | ⏳ 待阅读 |
| `第8章-事务.md` | 事务 | ⏳ 待阅读 |
| `第9章-分布式系统的麻烦.md` | 分布式系统的麻烦 | ⏳ 待阅读 |
| `第10章-一致性与共识.md` | 一致性与共识 | ⏳ 待阅读 |
| `第11章-批处理.md` | 批处理 | ⏳ 待阅读 |
| `第12章-流处理.md` | 流处理 | ⏳ 待阅读 |
| `第13章-流式系统的哲学.md` | 流式系统的哲学 | ⏳ 待阅读 |
| `第14章-将事情做正确.md` | 将事情做正确 | ⏳ 待阅读 |

## Subdirectories

| Directory | Purpose |
|-----------|---------|
| `fig/` | 原书插图 PNG 文件，按章节编号（详见 `fig/AGENTS.md`） |
| `map/` | 各章思维导图 PNG 文件，ch01–ch12（详见 `map/AGENTS.md`） |

## For AI Agents

### Working In This Directory
- 章节笔记 (`第N章-*.md`) 和精读笔记 (`第N章-精读笔记.md`) 是两类不同的文件：
  - **章节笔记**：原文摘录、关键概念整理
  - **精读笔记**：基于 Adler 分析阅读法，包含分类、大纲、关键字、主旨、论述结构
- 新增精读笔记时应遵循已有的 Adler 模板格式
- 更新阅读进度时需同步修改 `_index.md` 中的 checklist
- `目录.md` 中的链接指向 `Vonng/ddia` 翻译仓库的原始锚点，而非本地文件

### Common Patterns
- YAML frontmatter 用于章节笔记：`title`、`linkTitle`、`weight`、`breadcrumbs`
- YAML frontmatter 用于 `_index.md`：`tags`、`status`、`started`
- 插图文件名格式：`ddia_CCNN.png`（CC=两位章节号，NN=两位图片序号）
- 思维导图文件名格式：`chNN.png`（NN=两位章节号）
- 第三部分（第11-14章）为第二版新增内容

### Testing Requirements
- 内容正确性以原书原文和 [Vonng/ddia](https://github.com/Vonng/ddia) 翻译仓库为准
- 通过 Obsidian 反向链接面板验证章节之间的交叉引用

## Dependencies

### Internal
- `../_index.md` — 上级 MOC 入口，包含指向本书的链接
- `fig/` — 章节笔记中通过 `![[fig/ddia_CCNN.png]]` 引用插图
- `map/` — 独立导图文件，供快速回顾

### External
- **原书**：Martin Kleppmann, *Designing Data-Intensive Applications*, 2nd Edition
- **中文翻译**：[Vonng/ddia](https://github.com/Vonng/ddia) (GitHub)
- **原书官网**：[dataintensive.net](https://dataintensive.net/)

<!-- MANUAL: Any manually added notes below this line are preserved on regeneration -->
