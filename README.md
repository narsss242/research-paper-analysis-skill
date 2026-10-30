# 论文精读卡与证据分析 · research-paper-analysis-skill

Research paper analysis: a structured 16-section reading card covering methods, experiments, evidence and limitations.

适用于支持 Agent Skills 的 Codex 等智能体。工作流默认使用中文；实际 PDF、图像、文档、转写服务和脚本能力取决于接收者的运行环境。

## 快速开始

使用 Skills CLI 安装（需要 Node.js；按提示选择你的智能体）：

```bash
npx skills add narsss242/research-paper-analysis-skill
```

也可以下载 [独立 ZIP](https://github.com/narsss242/research-paper-analysis-skill/raw/refs/heads/main/packages/research-paper-analysis-skill.zip)，解压后把完整 `research-paper-analysis-skill` 文件夹放到所用客户端的技能目录。Codex 常用 `~/.codex/skills/`，以客户端设置为准。不要只复制 SKILL.md；保留 references、scripts、agents 等配套文件。

若通过 GitHub 的 Code → Download ZIP 下载，解压后的文件夹可能带 `-main` 后缀，安装前改为 `research-paper-analysis-skill`。已有旧版时先备份；不要同时启用旧名和新名两个副本。没有技能安装功能时，可让能读取本地文件的助手先阅读 [SKILL.md](SKILL.md)。

提供自己的材料后，输入：

```text
请使用 $research-paper-analysis-skill。
请为这篇论文制作16节精读卡，核对方法、实验、结论边界和后续研究想法。
```

## 输入与结果

具体输入、工作步骤、适用边界和验收要求见 [SKILL.md](SKILL.md)。这是给智能体执行的工作流，不是独立运行的转写引擎、OCR 引擎或文档应用；所需服务由接收者自己的环境提供。图片与论文结论须回查原材料，结构检查通过不等于学术事实核验完成。

## 可选的论文工作流

- [论文精读教练](https://github.com/narsss242/research-paper-reading-skill)
- [学术论文中英对照翻译](https://github.com/narsss242/academic-paper-translation-skill)
- [论文导读网页生成](https://github.com/narsss242/paper-explainer-webpage-skill)

上述技能分别安装；本技能的主要用途不依赖同时安装全部技能。

## 来源与版本

本项目从此前公开分享版独立发布，原调用名为 `nature-paper-card`。 基于 [Yuan1z0825/nature-skills](https://github.com/Yuan1z0825/nature-skills) 的 `nature-paper-card` 改编，保留 Apache-2.0 许可证、原作者信息及 [SOURCE.md](SOURCE.md)。

[全部学习与科研技能目录](https://github.com/narsss242/learning-and-research-skills) · [本地材料与服务配置](https://github.com/narsss242/learning-and-research-skills/blob/main/docs/configuration.md)
