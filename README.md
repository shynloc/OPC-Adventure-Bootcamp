# OPC Adventure｜新手村指南

一套面向普通人的 AI 协作实践指南：在真正开始经营一个 OPC（个人事业 / 工作室 / 品牌 / 独立项目 / One Person Company）之前，如何借助 AI 把自己、工作方式、品牌、视觉、内容生产系统和数字资产一件一件建立起来。

本项目按照软件开发的方式推进，而不是一次性写完一组文章。完整的项目原则、章节大纲、写作工作流、Definition of Done 等规则见 [PROJECT.md](./PROJECT.md)。

## 当前状态

规划阶段已完成，正文写作尚未开始。当前任务见 [TASKS.md](./TASKS.md)。

## 目录结构

```text
OPC Adventure/
│
├── PROJECT.md          项目定义 / 核心理念 / 写作系统 / 全部规则（Source of Truth）
├── README.md            本文件
├── TASKS.md              项目状态中心，章节进度与 Definition of Done 追踪
│
├── manuscript/           正文章节（唯一可信源，Website / PDF / EPUB 均由此构建）
├── research/              分章节研究资料，按 chapter-00 ~ chapter-08 划分
├── references/            分章节引用来源，最终聚合为 bibliography.md
├── assets/                 分章节图片 / 插图，及对应生成 Prompt
├── prompts/                可复用 Prompt 模板库
├── examples/               案例、截图、参考素材
├── build/                   最终输出（Markdown / Website / PDF / EPUB）
└── archive/                 旧版本存档
```

## 写作流程（每章）

Discussion → Research → Outline → Draft → 作者反馈 → Revision → Final Edit → References → Definition of Done → 更新 TASKS.md → Git Commit

详见 PROJECT.md 第 5、13、15 节。
