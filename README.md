# Storytelling

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL--3.0-blue.svg)](LICENSE)

**治好 AI 默认写“因为 A、所以 B、此外 C”上帝视角流水账的叙事发动机——注入预期落差、转折阻碍与悬念诱饵，让人情不自禁往下听。**

> 作者：阿祖不看 TVC（小红书同名）· [demyth.info](https://demyth.info) · [Lawyif@163.com](mailto:Lawyif@163.com)

---

## 一句话看懂：为什么 AI 写的故事总像“工作汇报”？

大模型默认是一台**全知上帝视角的说明文机器**：它喜欢第一段就把结论剧透干净，再用“第一、此外、与此同时、值得注意的是”把事按分类摆平。理性读者扫两眼就关掉了，因为**前面没有任何未知，后面也就没有任何期待**。

**Storytelling** 不是教它堆砌华丽形容词，而是把时间流动里的**阻力与不确定性**还回去——通过 5 个核心杠杆把静态说明变成认知推进：

1. **鸿沟（The Gap）**：没有“按计划走却撞墙反弹”的落差，只是流程汇报，不是故事；
2. **因果咬合（Therefore / But）**：砍掉“此外 / 另外 / 与此同时”，让每一段都只能是前一段的直接后果或意外打断；
3. **信息盲区与诱饵（The Bait）**：不在开场提前交底，始终在前方留一块“非补齐不可”的拼图；
4. **赌注（Stakes · 慎用）**：点出真实的窗口期成本或不可逆代价（绝不为煽情强行生死攸关）；
5. **顿悟反思（Reflection）**：在破局高潮处跳出一秒点出底层规律，让听众完成一次心智升级。

---

## 改写前后一眼看懂

| 常见 AI 说明文写法（上帝视角） | Storytelling 叙事改写（受限时间流视角） |
| --- | --- |
| “XX 品牌最初业绩不佳。**此外**，他们也面临渠道问题。**后来事实证明**，改做会员体系带来了成功，**因此**建议大家学习会员运营。” | “2023 年旺季打五折，流量却比去年少了一半——所有人都以为是投放没买够，**于是**加倍投流（Therefore），**但**复购率反而跌破盈亏线（But）。问题不在贵，而在一个被所有人忽略的习惯……” |

---

## 什么时候该用我 vs 什么时候千万别用

**注意边界：并不是“想写好一点”就一定要动用叙事杠杆。** 把一份只需要三秒看完结论的数据快报硬改成长篇故事，反而是在制造噪音。

| 你的任务场景 | 用哪个 Skill | 原因 |
| --- | --- | --- |
| 演讲稿、深度案例文章、比稿前情铺陈、需要拉动注意力的视频故事线 | **本 Skill (`storytelling`)** | 专注重构跨段落推进顺序、破局前铺垫与高潮反思节奏 |
| 写完要放上 PPT 屏幕的单页标题、证据卡片与 3 秒扫读句子 | 配合 [`slide-copy`](https://github.com/thePlannerIvan/slide-copy) | 我管宏观叙事推进怎么抓人；页面文案排版和句子规范归 `slide-copy` |
| 有了整案材料要展开完整 PPT 逐页正文与配图 | [`planners-bypage`](https://github.com/thePlannerIvan/planners-bypage) | 逐页正稿产出、核查与交付归 `bypage` |
| 只是检查文章错别字、语法与联网事实核查 | [`editor`](https://github.com/thePlannerIvan/editor) | `editor` 管校对与红绿修订页，不拆整篇叙事骨牌 |

---

## 快速开始与安装

### 1. 安装

**DSH 用户**：通过 [Planners Form](https://github.com/thePlannerIvan/planners-form) 安装 `planners-proposal` 或 `planners-bypage` 时会一并装好；之后在对话中可直接呼出 `storytelling`。

**Codex / Claude Code 用户：**

```bash
npx skills add https://github.com/thePlannerIvan/storytelling --skill storytelling
```

或克隆到本地 Skill 目录：

```bash
git clone https://github.com/thePlannerIvan/storytelling.git ~/.codex/skills/storytelling
# 或
git clone https://github.com/thePlannerIvan/storytelling.git ~/.claude/skills/storytelling
```

*(纯认知规范型 Skill：**零运行脚本与第三方依赖**，开箱即用。)*

### 2. 直接这样调用

```text
用 $storytelling 重构这份案例拆解/演讲底稿的推进结构：
事实和数字一条都不许编造或改动，去掉开头的上帝视角总结和“此外/另外”，用鸿沟与因果咬合重新编排段落顺序。
```

---

## 目录、协议与商业合作

- **目录构成**：`SKILL.md`（说明文 vs 叙事对比、5 大杠杆、节奏控制与剪枝准则）、`agents/openai.yaml`（界面元数据）。
- **许可与归属**：以 [AGPL-3.0-only](LICENSE) 发布；出处保留于 [NOTICE](NOTICE)，默认不进入客户最终交付物；商标边界见 [TRADEMARK.md](TRADEMARK.md)。
- **商业合作**：演讲与方案叙事体系搭建、企业内容培训或闭源授权，请联系 `Lawyif@163.com` 或访问 [demyth.info](https://demyth.info)，详见 [COMMERCIAL.md](COMMERCIAL.md)。
