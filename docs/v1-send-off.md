**English** | [**中文**](#中文)

# v1 Send-off — the pre-BP postcheck of the three-debater parliament

*The first at-scale, ground-truth measurement of the original Zealot / Reaper / Fulcrum parliament — and the data that retired it.*

## What this is

Before **BP** ([see the README](../README.md)) reshaped the system into v2, I ran the first proper postcheck of the old three-debater parliament: **n = 56** verdicts, scored at the **3-day** horizon against real prices (as_of 2026-07-02 → 07-13). Scoring is 0–100 — **0 = whiff** (wrong direction), **50 = miss** (right read, not acted on), **100 = hit** — and the pass line is a permanent, strict **70**.

## How the three-agent version did

- **Average score 67.6.**
- **52%** (29 / 56) cleared the 70 pass line; **18%** (10 / 56) nailed it (≥ 90).
- By region: **US 69.6** (n=47), **JP 66.6** (n=5), **EU 45.2** (n=4 — a small-sample false-low, two German-defense names selling off together on one day).

Three AIs arguing their way to a call, graded honestly against what the market actually did — that isn't a bad place for the three-debater era to end.

## The finding that sent it to v2

The same report measured the **Fulcrum** damper's net contribution and found it wanting: it destroyed value as often as it saved (**11 / 11**), and even its "saves" averaged only **58**, below the pass line — while the two-thirds of cases where it stayed out of the way scored best (**74.9**). The report also caught the debate behaving as a **centripetal compressor** (93% of sessions narrowed disagreement, yet only a **39%** right-rate) and the Bayesian concession rule leaning structurally bearish (the bull caved twice as hard as the bear).

Those three facts are exactly why v2 **retired Fulcrum**, opened a **directed-evidence** inlet, and **re-gated the Bayesian rule** on verified evidence. In BP terms, *this report is the gradient* that produced the first v2 weight update. (It also surfaced a real data bug — a 25% mislabel rate in a quant boolean — fixed in the same batch.)

## The full report

📄 **[postcheck-v1-pre-BP.pdf](postcheck-v1-pre-BP.pdf)** — the complete analysis (Chinese): per-region tables, the two failure-mode clusters, the damper net-value ledger, the round-by-round debate anatomy, and the B0–B6 improvement recommendations.

---

<a id="中文"></a>

[**English**](#english--中文) | **中文**

# v1 送别 —— 三辩手议会的 pre-BP 后验

*对最初那套 Zealot / Reaper / Fulcrum 议会的第一次成规模、ground-truth 度量 —— 也是把它退役的那份数据。*

## 这是什么

在 **BP**（[见 README](../README.md)）把系统重塑成 v2 之前，我给老版三辩手议会跑了第一次正经后验：**n = 56** 份判决，在 **3 天** 档位上对真实价格打分（as_of 2026-07-02 → 07-13）。评分 0–100 —— **0 踩空**（方向反）、**50 错过**（看对没动手）、**100 踩中** —— 及格线是永久、严格的 **70**。

## 三辩手版本考得怎么样

- **均分 67.6。**
- **52%**（29 / 56）过了 70 及格线；**18%**（10 / 56）踩中（≥ 90）。
- 分区：**美股 69.6**（n=47）、**日股 66.6**（n=5）、**欧股 45.2**（n=4 —— 小样本假性偏低，两只德国防务股同一天联动抛售拖累）。

三个 AI 吵出一个判断、再拿市场真实走势老实打分 —— 三辩手这一时代能收在这儿，其实不赖。

## 把它送往 v2 的那个发现

同一份报告量了 **Fulcrum** 阻尼器的净贡献，结论很难看：它**毁值和拦截一样多（11 / 11）**，连"拦对"的也均分只有 **58**、够不上及格线 —— 而它没插手、放辩论自己走的那三分之二场，反而考得最好（**74.9**）。报告还抓到辩论其实是台**向心压缩机**（93% 场次分歧收窄，推对率却只有 **39%**），以及贝叶斯退让规则结构性偏空（多头认怂的幅度是空头的两倍）。

这三条，正是 v2 **退役 Fulcrum**、开一个**定向取证**入口、把贝叶斯退让**重设到 verified 证据门槛**的直接原因。用 BP 的话说，*这份报告就是那个梯度* —— 它跑出了 v2 的第一次权重更新。（它还顺带揪出一个真实数据 bug —— 某个量化布尔值 25% 的错标率 —— 同批修掉了。）

## 完整报告

📄 **[postcheck-v1-pre-BP.pdf](postcheck-v1-pre-BP.pdf)** —— 完整分析（中文）：分区表、两簇失手镜像、阻尼器净值核算、逐轮辩论解剖，以及 B0–B6 改进建议。
