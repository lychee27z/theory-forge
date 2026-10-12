<div align="center">

# 🔥 theory-forge · 论之锻造炉

**把你憋在心里的那个观察，锻造成一个能刷屏的「xxx 论」。**

一组免费开放的 AI Skill · 支持 Claude Code / Claude.ai / 任何能读 Markdown 的 Agent

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hans)

[30 秒看效果](#30-秒看效果) · [安装](#安装) · [完整示例](examples/prepaid-discipline.md) · [English](#english)

</div>

---

## 先说一个规律

你有没有发现，一个观点能不能传开，跟它对不对关系不大，**跟它有没有名字关系很大**？

「大家都更拼了，结果谁也没变好」，这件事早就存在。直到它被叫做**内卷**，所有人才突然开始聊它。

我管这个叫 **命名权定律**：

> **谁先给一个现象起了名字，谁就拥有了这个现象。**

你脑子里一定也有几个这样的观察，只是它还没有名字。

这个仓库就是干这个的。

---

## 30 秒看效果

你说一句：

> 我发现很多人买健身卡不是为了健身，是为了买一个「我在变好」的感觉。

它先追问你两三句，然后给你：

> ## 🔥 预付自律论
> **我们花钱买的不是服务，是提前到账的自律感。**
>
> 你有没有发现，办健身卡那天，是你一整年最自律的一天？
>
> 一月一号，你办了张年卡。付款成功那一刻，你感觉自己已经瘦了五斤。然后你去了三次……
>
> **二创模板**：「___ 也是一种预付自律：我买了 ___，就觉得自己 ___ 了。」

再附上 Top 3 候选名打分、小红书 / 抖音口播 / 一句话版本、评论区会怎么杠你以及怎么接。

👉 [看完整输出](examples/prepaid-discipline.md)

再看一个理论体的完整样子，从一句「社交距离」出发：

> # 🔥 存档友谊论
> > **档还在，就够了。**
>
> **第一定律 · 存档律**：友谊不会因为不联系而消失，只会存档。
>
> **第二定律 · 默契律**：不打扰，是对存档的保护。
>
> **第三定律 · 读档律**：每次读档，读出来的不只是朋友，还有存档时的那个自己。
>
> **术语**：读档 · 存档点 · 心跳包 · 云存档 · 空存档位 · 坏档 · 删档

👉 [看完整理论体](examples/save-file-friendship.md)

---

## 它怎么做到的

一个「论」能火，大概要具备五个要素：

| 要素 | 自检 |
|---|---|
| **具象命名** | 5 秒内脑子里有画面吗？ |
| **反常识** | 看完会说「卧槽好像是」吗？ |
| **万物可套** | 能写出 3 个不同领域的「XX 也是一种 X」吗？ |
| **站队张力** | 评论区会吵起来吗？ |
| **可二创** | 有没有一个句式让别人填自己的版本？ |

`theory-forge` 把这五点拆成了一条流水线：

```
追问挖掘 → 提纯断言 → 6 种公式命名 + 打分 → 构建理论体（三定律 · 术语表 · 推论 · 边界 · 自测）→ 预演评论区 → 红线自检
                                                                       ↘ 按需：爆点长文 / 多平台文案
```

**它产出的是一套理论，不是一篇文章。** 文章只能被读，理论能被用：引用一条定律、用一个术语描述自己、拿自测题问朋友、在评论区争论边界。

**它会先追问再动笔。** 多数人的想法一开始都是模糊的，好的追问比好的文笔更值钱。

## 包含的 Skill

| Skill | 一句话 |
|---|---|
| [`theory-forge`](skills/theory-forge/SKILL.md) | 一段思考 → 一个完整的「论」 |
| [`theory-remix`](skills/theory-remix/SKILL.md) | 一个「论」→ 小红书 / 抖音 / 知乎 / 英文 Thread… |
| [`theory-stress-test`](skills/theory-stress-test/SKILL.md) | 发之前，先让 AI 扮演评论区骂你一遍 |

参考资料：[理论体解剖](skills/theory-forge/references/theory-anatomy.md) · [命名公式](skills/theory-forge/references/naming-patterns.md) · [爆点结构](skills/theory-forge/references/viral-structures.md) · [拆解样本](skills/theory-forge/references/case-library.md) · [平台格式](skills/theory-forge/references/platform-formats.md) · [红线](skills/theory-forge/references/red-lines.md)

## 安装

**Claude Code（推荐）**

```bash
/plugin marketplace add lychee27z/theory-forge
/plugin install theory-forge@theory-forge
```

**手动**

```bash
git clone https://github.com/lychee27z/theory-forge.git
cp -r theory-forge/skills/* ~/.claude/skills/
```

**Claude.ai**：把 `skills/theory-forge` 打包成 zip，在 Settings → Capabilities → Skills 上传。

**其他 AI（ChatGPT / Kimi / 豆包…）**：把 [`SKILL.md`](skills/theory-forge/SKILL.md) 全文贴给它，说「按这个流程帮我」。

## 用法

```
帮我把这个想法做成一个论：我发现……
```

## 🏆 论之殿堂

**用它做出了你自己的论？** [提一个 Issue](https://github.com/lychee27z/theory-forge/issues/new?title=%E6%88%91%E7%9A%84%E8%AE%BA%EF%BC%9A&body=%E5%90%8D%E5%AD%97%EF%BC%9A%0A%E4%B8%80%E5%8F%A5%E8%AF%9D%EF%BC%9A%0A%E5%8F%91%E5%9C%A8%E5%93%AA%E4%BA%86%EF%BC%88%E9%93%BE%E6%8E%A5%EF%BC%89%EF%BC%9A)，标题写「我的论：XXX」。传播得好的会收录进这里，署你的名字。

| 论 | 一句话 | 作者 |
|---|---|---|
| 命名权定律 | 谁先给一个现象起了名字，谁就拥有了这个现象。 | [@lychee27z](https://github.com/lychee27z) |
| 预付自律论 | 我们花钱买的不是服务，是提前到账的自律感。 | [@lychee27z](https://github.com/lychee27z) |
| 存档友谊论 | 成年人友谊的本质，是互相不添麻烦的默契。 | [@lychee27z](https://github.com/lychee27z) |
| *你的论* | *等你* | *你* |

## 一条底线

**张力来自揭示一个机制，而不是贬低一类人。** 靠骂某个群体火起来的论，火得快，塌得也快，还会连累作者。所以 skill 内置了[红线自检](skills/theory-forge/references/red-lines.md)，碰到这类内容会帮你改写，不会拒绝写。

## 贡献

- 往[拆解样本库](skills/theory-forge/references/case-library.md)里加你熟悉的网络理论（薄肌理论、黄毛理论、大水理论……我们缺懂出处的人）
- 往 [evals](evals/cases.json) 里加测试用例
- 详见 [CONTRIBUTING.md](CONTRIBUTING.md)

**觉得有意思的话，点个 ⭐，或者把「命名权定律」讲给一个朋友听，也是在验证它。**

## 协议

[CC BY-NC-SA 4.0](LICENSE)：

- ✅ 个人使用、学习、分享、修改都可以
- ✅ 用它生成的「论」归你自己，你可以随便发、随便用
- 📝 转载或改编本仓库内容，需要署名并附上仓库链接
- 🔁 改编后的版本也必须用同样的协议
- ❌ 不得将本仓库内容用于商业目的（如收费课程、付费产品、商业 SaaS）

需要商用授权请[联系作者](https://github.com/lychee27z)。

---

## English

**theory-forge** is a set of free, source-available AI skills (CC BY-NC-SA 4.0, non-commercial) that turns a half-formed personal observation into a named, shareable "theory": the kind of meme-concept (*broken windows*, *sunk cost*, *involution*) people instantly get, apply to their own lives, and repeat to others.

It interviews you first, distills a counter-intuitive claim, generates and scores names across six naming formulas, writes the piece in a hook-driven seven-part structure, adapts it per platform, simulates the comment section to stress-test it, and checks that its edge comes from insight, not from attacking a group. Content is primarily Chinese-internet oriented; English output is supported.

> **The Law of Naming Rights:** whoever names a phenomenon first, owns it.
