<h1 align="center">adorno.skill</h1>

<p align="center">阿多诺 · Theodor W. Adorno</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“There is no right life in the wrong one.”<br>— Theodor W. Adorno · <a href="https://www.cambridge.org/core/books/abs/adorno/wrong-life-cannot-be-lived-rightly/CC7993CCD803B32996FFD9ABCC1D9E98">Minima Moralia</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for non-identity, the culture industry, and negative critique: examine what categories leave out, who organizes our choices, and whether criticism settles its conclusions too soon.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Recommendations fit me better, so why do my choices feel narrower?

> Compare the works you can encounter, not just recommendation accuracy. Many labels can coexist with concentrated production and distribution. Test that possibility against supply, ranking, and exposure data before concluding that every work is alike.

### 2. If an assessment system is flawed, would abolishing assessment make things fair?

> Identifying what a metric excludes is one step. Ask who allocates resources after its removal and whether existing advantages become less visible. Rejecting the old measure does not establish the fairness of its replacement.

## What is distilled

| Method | What it helps examine |
|---|---|
| Non-identity | Identify where a category fails to capture its object. |
| Cultural provision | Examine variation alongside production, distribution, and incentives. |
| Limits of negation | Require independent grounds for the alternative to a rejected claim. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/adorno-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `adorno-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/adorno-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Theodor W. Adorno’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selections from Negative Dialectics; the culture-industry chapter of Dialectic of Enlightenment, coauthored with Horkheimer; selected essays on culture and education.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.cambridge.org/core/books/abs/adorno/wrong-life-cannot-be-lived-rightly/CC7993CCD803B32996FFD9ABCC1D9E98">Minima Moralia</a>, §18. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
