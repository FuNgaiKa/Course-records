# File Organization

本文档说明本仓库的目录职责和文件命名规范。

## Top-level Directories

```text
courses/    课程资料
planning/   时间安排和学习计划
misc/       非课程类备忘
docs/       仓库说明和维护规范
```

## Course Directories

课程相关内容统一放在 `courses/` 下，并按课程建立子目录。

推荐目录命名使用英文短横线格式：

```text
courses/machine-learning/
courses/cloud-computing/
courses/communication-principles/
```

每门课程目录中可以包含：

- 课程目录
- 复习笔记
- 作业记录
- 实验报告
- 小组分工
- 参考资料整理

## File Naming

Markdown 文件优先使用清晰中文名称，便于直接阅读和检索。

推荐示例：

```text
机器学习复习.md
机器学习实验感想和分工.md
云计算作业.md
通信原理作业.md
考试时间.md
```

如果同类文件较多，可在文件名前增加日期或序号：

```text
2026-07-06-机器学习考前复习.md
01-课程介绍.md
02-频繁项集挖掘.md
```

## Writing Rules

1. 一个文件只表达一个明确主题。
2. 标题层级从 `#` 开始，避免直接从三级标题开始。
3. 长篇内容按章节拆分，避免单个文件难以维护。
4. 引用外部资料时保留链接或来源说明。
5. 代码、命令和公式尽量使用 Markdown 代码块或明确格式。

## Git Rules

1. 不提交系统缓存、编辑器缓存、运行产物和临时文件。
2. 调整目录结构时，尽量不同时大幅改写正文内容。
3. 正文修改建议按课程或主题分批提交，方便回溯。
