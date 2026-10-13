<h1 align="center">adorno.skill</h1>

<p align="center">阿多诺 · Theodor W. Adorno</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“在错误的生活中，没有正确的生活。”<br>— 阿多诺 · <a href="https://www.cambridge.org/core/books/abs/adorno/wrong-life-cannot-be-lived-rightly/CC7993CCD803B32996FFD9ABCC1D9E98">《最低限度的道德》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将非同一性、文化工业批判与否定思维整理为思想分析 Skill，让 AI 追问分类遗漏了谁、选择由谁安排，以及批评是否过早宣布了答案。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 推荐越来越精准，为什么我反而觉得选择变少了？

> 先比较你能接触到的作品，而不只看推荐命中率。界面上的细分标签可能很多，背后的生产和分发渠道却很集中；需要用供给、排序与曝光材料检验这一点，不能凭体验就断定所有作品相同。

### 2. 这个评价体系有问题，所以完全取消评价就公平了吗？

> 发现一个尺度排除了什么，只完成了批评的一步。取消它之后，资源由谁分配、原有优势是否更隐蔽，都需要继续考察；反对旧尺度不会自动证明新安排公正。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 非同一性 | 检查具体对象与分类之间的不相称，保留被标签抹去的细节。 |
| 文化供给 | 把作品差异与生产、分发、收益安排放在一起分析。 |
| 否定的限度 | 反驳一个结论后，继续检查替代结论是否有自己的根据。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/adorno-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `adorno-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/adorno-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用阿多诺的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《否定辩证法》选段；与霍克海默合著的《启蒙辩证法》文化工业章；文化工业与教育文章选段。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.cambridge.org/core/books/abs/adorno/wrong-life-cannot-be-lived-rightly/CC7993CCD803B32996FFD9ABCC1D9E98">《最低限度的道德》</a>，第 18 则；链接为引述该句的学术研究。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
