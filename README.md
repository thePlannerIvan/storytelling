# Storytelling

把事实与因果组织成有张力、有推进的叙事。

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](LICENSE)

作者：阿祖不看 TVC · 小红书同名账号 · [demyth.info](https://demyth.info) · Lawyif@163.com

## 使用方式

调用名：`storytelling`。商业提案、演讲、深度文章、案例拆解和视频脚本。不代替事实核查、资料研究或视频制作。

识别预期与现实的落差，组织因果推进和信息揭示，校准阻力与赌注，在关键节点提炼认识，最后回应开场问题。

```text
用 storytelling 改写这份提案的主线：保留已有事实，让每一章自然引出下一章。
```

## 安装

```bash
npx skills add https://github.com/thePlannerIvan/storytelling --skill storytelling
```

也可以克隆到支持 Skill 的 Agent 目录（以下为 Claude Code）：

```bash
git clone https://github.com/thePlannerIvan/storytelling.git ~/.claude/skills/storytelling
```

在 DSH 中，Planners Form 会随调用本组件的配套 Skill 安装它；安装后仍可通过 `storytelling` 独立调用。它没有独立审阅页，不在 Planners Form 设置中单列。

没有额外脚本运行时或审阅页依赖。

## 目录

`SKILL.md`：叙事原则与检查标准；`agents/openai.yaml`：界面元数据。

## 开源与归属

许可文本见 [LICENSE](LICENSE)（AGPL-3.0）。作者和来源见 [NOTICE](NOTICE)，名称使用边界见 [TRADEMARK.md](TRADEMARK.md)，合作入口见 [COMMERCIAL.md](COMMERCIAL.md)。署名用于仓库和工作过程，默认不加入最终客户交付物。
