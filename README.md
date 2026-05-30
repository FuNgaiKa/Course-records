# Course Records

课程资料、作业记录和复习笔记归档仓库。

本仓库用于集中管理大学课程相关资料，包括课程目录、复习笔记、课程作业、实验总结、考试安排以及少量非课程备忘。目录按用途和课程拆分，方便后续持续补充和检索。

## Repository Structure

```text
.
├── courses/
│   ├── cloud-computing/
│   │   └── 云计算作业.md
│   ├── communication-principles/
│   │   └── 通信原理作业.md
│   └── machine-learning/
│       ├── 机器学习目录.md
│       ├── 机器学习复习.md
│       └── 机器学习实验感想和分工.md
├── docs/
│   └── FILE_ORGANIZATION.md
├── misc/
│   └── 篮球轮转.md
├── planning/
│   └── 考试时间.md
├── .gitignore
└── README.md
```

## Directory Guide

- `courses/`: 按课程归档的学习资料、作业、实验记录和复习笔记。
- `planning/`: 考试时间、学习计划、阶段安排等时间管理类内容。
- `misc/`: 与课程无直接关系，但仍希望保留在仓库中的个人备忘。
- `docs/`: 仓库维护说明和文件组织规范。

更详细的文件归档规则见 [docs/FILE_ORGANIZATION.md](docs/FILE_ORGANIZATION.md)。

## Usage

常用查看方式：

```bash
find . -maxdepth 3 -type f | sort
```

按关键词搜索：

```bash
rg "PageRank"
```

## Maintenance Rules

1. 新增课程资料优先放入 `courses/<course-name>/`。
2. 每门课程保持独立目录，不把不同课程的作业和复习笔记混放。
3. 文件名使用清晰中文标题，必要时加上日期或阶段说明。
4. 原始内容优先保留，结构整理和正文润色分开提交。
5. 临时文件、缓存文件和本地 IDE 配置不提交到仓库。

## Status

当前仓库以 Markdown 资料为主，没有构建、测试或运行入口。
