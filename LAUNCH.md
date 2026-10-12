# 发布文案包

> 复制即用。每个平台换了不同的钩子，避免同一个人多处刷到时觉得在复读。
> 仓库链接：https://github.com/lychee27z/theory-forge

## 发布顺序建议

1. **即刻 / V2EX / 少数派**（技术 + 早期用户圈，先拿第一波 star 和反馈）
2. **小红书 / 抖音**（用「预付自律论」做内容本身，仓库放评论区或简介。**内容先火，工具后露出**）
3. **X / Twitter**（英文 Thread，打 AI Skills 圈子）
4. 把用户投稿的好论**转发回去**，形成「用户的论 → 带来新用户」的循环

---

## 即刻 / 朋友圈

> 发现一个规律：一个观点能不能传开，不看它对不对，看它有没有名字。
>
> 我管这个叫「命名权定律」：谁先给一个现象起了名字，谁就拥有了这个现象。
>
> 所以做了个免费开放的 AI skill，专门帮人把脑子里的观察锻造成一个「xxx 论」。会先追问你，再起名、打分、写成能传播的结构，还会预演评论区怎么杠你。
>
> 试了一下，「办健身卡不是为了健身」被它锻造成了「预付自律论」。
>
> github.com/lychee27z/theory-forge

## V2EX（分享创造）

**标题**：做了个免费开放的 Claude Skill：把你的想法锻造成一个能刷屏的「xxx 论」

> 最近网上各种「xx 理论」很火，我拆了一下，发现能火的论都有五个共同点：具象命名、反常识、万物可套、站队张力、可二创。
>
> 就把这套结构写成了一组 Skill（Claude Code 可以直接装，其他 AI 贴 SKILL.md 也能用）：
>
> - theory-forge：追问 → 提纯 → 6 种公式命名并打分 → 七段式成文 → 多平台改写 → 预演评论区 → 红线自检
> - theory-remix：一个论改写成小红书 / 抖音口播 / 知乎 / 英文 Thread
> - theory-stress-test：发之前先让 AI 扮演评论区骂你一遍
>
> 一个设计取舍：内置了红线自检，碰到群体标签类的内容会改写成「机制」而不是直接拒绝。
>
> 完整示例（预付自律论）在 README 里。欢迎来提 issue 投稿你的论。
>
> https://github.com/lychee27z/theory-forge

## 小红书

**封面字**：我给 AI 装了个「造论机」

**标题**：薄肌理论、黄毛理论之后，人人都能有自己的论

> 你有没有那种：心里早就看透了一件事，但说不出个名堂？
>
> 名字，就是一个观点能不能传开的关键。
> 「大家都更拼了谁也没变好」早就有了，叫它「内卷」之后才火。
>
> 所以我做了个免费的 AI 工具👇
> 你说一句吐槽，它会：
> 1️⃣ 先追问你，把想法挖清楚
> 2️⃣ 给你起 10 个名字并打分
> 3️⃣ 写成「一看就想转发」的结构
> 4️⃣ 出小红书 / 抖音 / 朋友圈版本
> 5️⃣ 提前模拟评论区怎么杠你
>
> 我试了一句「买健身卡不是为了健身」
> 它给我锻造出了：**预付自律论**
> 「我们花钱买的不是服务，是提前到账的自律感」
>
> 你脑子里有什么还没有名字的观察？评论区说，我挑几个帮你锻造🔥
>
> #AI工具 #理论 #自我成长 #小红书创作 #Claude

## 抖音口播（约 50 秒）

> [举着健身卡] 这张卡我去了三次，但办卡那天我觉得自己已经瘦了。
> [停顿] 我管这个叫，预付自律论。
> 这个名字，不是我想的。[停顿] 是 AI 帮我锻造的。
> 我做了个免费工具，你跟它说一句吐槽，它先追问你，再帮你起名、打分、写成能火的结构，还会提前模拟评论区怎么骂你。
> 薄肌理论、黄毛理论，都是一个人先看透了一件事，再给它起了名字。
> 你脑子里一定也有一个。[停顿]
> 评论区告诉我，我帮你锻造。

## X / Twitter（英文 Thread）

> 1/ The Law of Naming Rights: whoever names a phenomenon first, owns it.
> "Involution", "sunk cost", "broken windows". The ideas existed long before; the names made them spread.
>
> 2/ So I built theory-forge: free Claude Skills that turn a half-formed observation into a named, shareable theory.
>
> 3/ It interviews you first, then distills a counter-intuitive claim, generates and scores names across 6 naming formulas, and writes it in a hook-driven structure.
>
> 4/ Then it simulates your comment section to stress-test the idea, and rewrites anything that relies on attacking a group into an actual mechanism.
>
> 5/ Example: "people buy gym memberships to buy the feeling of getting better" → **Prepaid Discipline**: you're not paying for the service, you're paying for discipline delivered in advance.
>
> 6/ Free for non-commercial use (CC BY-NC-SA 4.0). Install in Claude Code:
> /plugin marketplace add lychee27z/theory-forge
> github.com/lychee27z/theory-forge

---

## 让它自己转起来的机制（已内置在仓库里）

- **README 本身就是一个论**（命名权定律）：看的人会先被这个论吸引，然后才看到工具
- **论之殿堂**：用户投稿会署名收录，作者有动力自己去转发
- **二创模板**：每个生成的论都带「___ 也是一种 X」的句式，天然鼓励评论区接龙
- **仓库 Topics 建议**：`claude-skills` `ai-writing` `prompt-engineering` `chinese` `content-creation` `viral`
