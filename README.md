<p align="center">
  <img src="https://www.ncu.edu.cn/images/logo.png" alt="南昌大学标识" width="280">
</p>

<h1 align="center">南昌大学课程实验作品集</h1>

<p align="center">环境工程 · 2026 学年课程实验记录</p>

## 个人信息

| 项目 | 内容 |
| --- | --- |
| 学校 | 南昌大学 |
| 姓名 | 高子航 |
| 学号 | 5807126092 |
| 专业班级 | 环境工程264班 |

## 学期实验目录

```text
.
├── README.md
├── .gitignore
└── experiments
    ├── week-01
    ├── week-02
    ├── week-03
    ├── week-04
    ├── week-05
    ├── week-06
    ├── week-07
    ├── week-08
    ├── week-09
    ├── week-10
    ├── week-11
    ├── week-12
    ├── week-13
    ├── week-14
    ├── week-15
    └── week-16
```

每周实验请放入对应文件夹。建议每周记录实验目的、步骤、结果、遇到的问题和个人总结；图片及数据文件也可以放在当周目录中。

## 单摆交互模拟器

打开根目录的 `index.html`，即可运行使用原生 HTML、CSS 和 Canvas 实现的单摆模拟器。也可以通过 [GitHub Pages 在线体验](https://serendipityas.github.io/ncu-environment-engineering-portfolio-5807126092/)。

## 人机协同三点反思

### 1. 意图设计思考

编写初始 Prompt 时，我特意要求应用采用“单文件、不依赖外部库”，避免 CDN 网络加载失败，确保双击即可运行 MVP。

### 2. 报错自愈思考

点击重置按钮出现 `ReferenceError` 时，我把报错名称和行号提供给 AI，借助错误信息排查重置函数的作用域与事件绑定问题，并通过代码检查确认修复。

### 3. 人机协同哲学反思

AI 协助编写了大部分 Canvas 代码；我负责确定物理模型、界面视觉要求，并检查交互功能是否符合预期。AI 帮助加快实现，人负责明确目标和验收结果。
