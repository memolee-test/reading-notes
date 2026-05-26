<!-- Parent: ../AGENTS.md -->
<!-- Generated: 2026-05-15 | Updated: 2026-05-15 -->

# 读书笔记

## Purpose
读书笔记的内容根目录，采用 MOC（Map of Content）模式组织。`_index.md` 作为入口页面，通过 Wiki 链接串联所有书籍笔记。当前聚焦技术架构类书籍，以 DDIA 为核心。

## Key Files

| File | Description |
|------|-------------|
| `_index.md` | MOC 入口页 — 列出所有在读书籍、分类目录、笔记模板 |
| `未命名.md` | 空白笔记草稿，待整理或删除 |

## Subdirectories

| Directory | Purpose |
|-----------|---------|
| `DDIA-第二版/` | 《数据密集型应用系统设计》第二版精读笔记（详见 `DDIA-第二版/AGENTS.md`） |

## For AI Agents

### Working In This Directory
- `_index.md` 是导航中心，新增书籍时需在此文件中添加链接和元数据
- 每本书应在其独立子目录中组织，目录名格式：`书名-版本/`
- 新书目录内可参照 DDIA-第二版的结构：章节笔记 + 精读笔记 + 插图 + 思维导图

### Common Patterns
- 使用 Obsidian `tags` frontmatter 标注笔记类型：`reading`（阅读中）、`book`（书籍）、`moc`（索引页）
- `status` 字段取值：`reading`（阅读中）、`completed`（已完成）、`paused`（暂停）
- 书籍的第一层 `_index.md` 包含：元数据（作者、版本、状态）、阅读进度清单、章节导航、核心概念速查表

### Testing Requirements
- 无自动化测试 — 确保 Wiki 链接路径与实际文件匹配即可
- 使用 Obsidian 的「出链」功能检查 `_index.md` 中的链接是否有死链

## Dependencies

### Internal
- `../.obsidian/` — Obsidian 配置影响笔记编辑体验
- `DDIA-第二版/` — 当前唯一的书籍笔记子目录

### External
- **Obsidian** — 编辑与链接验证

<!-- MANUAL: Any manually added notes below this line are preserved on regeneration -->
