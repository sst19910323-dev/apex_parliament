# 插画生成提示词 / Illustration Prompts

> 用途：把这份文件喂给任意图像生成 AI（Midjourney / DALL·E / SD / 即梦 / 通义万相均可），为《设计哲学》16 条各生成一张成套的卡通插画。
> 用法：**先把下面的「全局风格」和「角色设定」一次性给到模型**（很多图像模型不跨图记忆，所以每条提示词里我都把风格关键词复述了一遍）。然后逐条生成。
> 编号与《[设计哲学](design-philosophy.md)》一一对应。
> 语言：主提示词用英文（图像模型对英文最敏感），中文仅作对照。

---

## 全局风格 / Global Style (paste this first)

```
STYLE BIBLE — keep consistent across all images:
Flat editorial cartoon illustration, in the spirit of a witty New Yorker / Monocle
spot illustration but more playful. Clean vector-like shapes, bold confident
outlines, slightly hand-drawn wobble. Warm limited palette: paper-cream background,
charcoal linework, and exactly three accent colors used as character codes —
WARM RED (the optimist), COOL BLUE (the realist), NEUTRAL GREY (the damper).
Generous negative space, single clear visual metaphor per image, gentle humor,
no text/letters/numbers baked into the image, no photorealism, no 3D render,
square 1:1 composition.
```

中文：扁平编辑式卡通，《纽约客》式的机智 spot illustration 但更俏皮。米白纸底、炭黑线条，三个固定强调色作为角色代码——暖红=乐观者、冷蓝=现实者、中性灰=阻尼器。大量留白，一图一个清晰隐喻，温和幽默，**画面里不要出现任何文字/字母/数字**，不要写实、不要 3D，正方形构图。

---

## 角色设定 / Character Sheet (paste this second)

```
RECURRING CAST — design once, reuse everywhere:
- ZEALOT: a warm-red rounded character, eager and bright-eyed, always leaning
  forward / looking up. The eternal optimist who wants to hold on. (NOT a bull
  mascot — a friendly little person/blob.)
- REAPER: a cool-blue character, calm and skeptical, one eyebrow raised. NOT a
  grim reaper, NOT a bear — a level-headed profit-taker who asks "is this still
  worth holding?"
- FULCRUM: a neutral-grey character balanced on a small pivot/seesaw, perfectly
  centered, unbothered. The damper. Default mood: serene neutrality.
- CHRONICLER: a small monk-like scribe with a quill and scroll, eyes closed,
  never touches the data — only transcribes. Off to the side.
- DATA OFFICER: a tidy clerk at an intake desk with a stamp, inspecting incoming
  paper slips for authenticity. Appears only where provenance matters.
- THE THREE TEMPERAMENTS (only for image #11): a stubborn CONTRARIAN who argues
  with everyone and ends up parroting himself; a soft PEOPLE-PLEASER who caves and
  waves a tiny white flag; a BRILLIANT one who writes one long elegant scroll and
  is already done. Generic AI-blob characters, NOT real-brand logos.
Keep their shapes, colors, and personalities identical across every illustration.
```

---

## 逐条提示词 / Per-Principle Prompts

### 1 — 会说不等于会做 / Talking ≠ Doing
```
A polished AI character in a tidy analyst's suit at a desk, calmly dictating an
elegant report from its mouth — but UNDER the desk its hands are frantically,
chaotically slamming up/down levers like a panicking gambler. Split between
"eloquent above, retail-panic below." [apply STYLE BIBLE]
```
中文：上半身西装革履、口吐优雅报告；桌子底下两只手却像赌徒一样疯狂乱拍升降杆。上文雅、下慌乱的反差。

### 2 — 乐观者的镜像是止盈者 / The Optimist's Mirror Is the Profit-Taker
```
The warm-red ZEALOT character stands facing a mirror, but the reflection is NOT a
sad pessimist — it is the cool-blue REAPER, calmly checking a pocket watch / weighing
a small scale, asking "still worth holding?". Optimist and profit-taker as mirror
images, not optimist vs. bear. [apply STYLE BIBLE + CHARACTER SHEET]
```
中文：暖红 Zealot 照镜子，镜中不是悲观者，而是冷蓝 Reaper 在淡定地掂量"还值不值得拿"。乐观者与止盈者互为镜像。

### 3 — 稳定来自动态 / Stability Comes From Motion
```
A character riding a bicycle stays perfectly upright BECAUSE it's moving fast;
behind/around it, ZEALOT, REAPER and FULCRUM are in a lively three-way tug-of-war,
yet a needle/gauge between them points dead-center and steady. Chaos at the edges,
calm at the center. [apply STYLE BIBLE + CHARACTER SHEET]
```
中文：骑车的人靠速度才立得稳；三个角色三方拉扯吵闹，可正中间的指针却稳稳指向中位。边缘越乱，中心越稳。

### 4 — 连续性必须挣得 / Continuity Must Be Earned
```
Two side-by-side paths. LEFT: a blindfolded character walking by dead-reckoning
from its own last footprint, drifting in a curve off course (inertial drift).
RIGHT: the same character re-fixing its position against a fixed star/lighthouse
each step, walking a true straight line. [apply STYLE BIBLE]
```
中文：左边蒙眼的人只参照自己上一个脚印，越走越偏；右边的人每步都对着固定的灯塔/星辰重新定位，走出真正的直线。

### 5 — 后视镜里没有方向盘 / No Steering Wheel in the Rearview Mirror
```
A little car where the driver is trying to steer using ONLY the rearview mirror —
the mirror is huge and detailed (showing the road already travelled) but there is
NO steering wheel and the windshield ahead is blank/foggy. Looking backward can't
drive you forward. [apply STYLE BIBLE]
```
中文：开车的人只盯着巨大的后视镜（清晰映出已走过的路），却根本没有方向盘，前挡风一片空白迷雾。看后方开不动前路。

### 6 — 别恳求模型，雕琢管线 / Sculpt the Pipeline, Don't Beg the Model
```
LEFT: a person kneeling and praying to a glowing "AI" idol/oracle, hopeful but
helpless. RIGHT: a calm engineer at a workbench precision-machining a clean
pipeline / fitting a well-spec'd component into a machine. Small inset: three tipsy
characters failing to prop each other up in a straight line. [apply STYLE BIBLE]
```
中文：左边的人对发光的"AI"神像跪拜祈求；右边的工程师在工作台上精密打磨管线、把规格件装进机器。角落小插图：三个醉汉互相搀扶却站不成直线。

### 7 — 穷是位老师 / Poverty Is a Teacher
```
Diptych. LEFT: a wealthy character lounging on a giant money pile, soft and
formless, capability without structure. RIGHT: a thrifty student with a single
coin, building an elegant rigid scaffold/skeleton out of toothpicks — lean but
structurally sound. Caption-free. [apply STYLE BIBLE]
```
中文：左边富人躺在钱堆上，松软无形（有能力没结构）；右边穷学生只有一枚硬币，却用牙签搭出精巧坚固的骨架。富长能力，穷长结构。

### 8 — 名局藏在"我以为它疯了" / The Brilliant Move
```
The CREATOR character clutching its head in shock at a verdict card the AI just
handed over (the card shows a bold DOWN-arrow — looks insane given everything is
green). Above, a small thought-bubble window into the near future shows the market
chart proving the call right. A chess-style sparkle "brilliant move" glint on the
card. Disbelief now, vindication later. [apply STYLE BIBLE]
```
中文：创造者捂着头被 AI 递过来的判决卡惊到（卡片上是个醒目的向下箭头——明明一片绿，却给卖出，看着像疯了）。上方一个通向不久后未来的思想气泡，显示行情图证明它是对的。卡片上有国际象棋"妙手"式的闪光。当下错愕，事后封神。

### 9 — 错得和对的一样好看 / Wrong That Looks As Good As Right
```
Two identical-looking beautiful framed reports hanging side by side, equally
elegant on the surface. Below each, a thin trail of footprints on stepping stones:
the left trail lands solidly on every stone (real data); the right trail has ONE
footstep stepping into empty air / a missing stone. Identical above, one misstep
below. [apply STYLE BIBLE]
```
中文：并排两份同样精美的报告，表面无从分辨。下方各有一串踩在垫脚石上的脚印：左边步步踏实（真数据），右边有一脚踩空。表面相同，链条上有一脚踩空。

### 10 — 辩论信息量守恒 / Conservation of Information
```
The same fixed amount of water (one jug) being poured into glasses. LEFT: poured
into MANY small glasses (many short rounds). RIGHT: poured into a FEW tall glasses
(few long rounds). Same total volume, different packaging. A clever blue character
fills few-tall; a plainer one fills many-small. [apply STYLE BIBLE + CHARACTER SHEET]
```
中文：同一壶水（信息总量固定）倒进杯子：左边倒进很多小杯（多轮短），右边倒进少数高杯（少轮长）。总量相同，只是打包方式不同。

### 11 — 模型各有脾气 / Models Have Personalities (and high temperature is fine)
```
Center hero: a big friendly temperature/heat dial whose needle sits HIGH yet the
character beside it is calm and creative (high-T = fine, not chaotic); a tiny
low-setting corner shows a rigid wind-up parrot, stiff and repeating. Around the
dial, three distinct AI-blob temperaments at a round table: a stubborn CONTRARIAN
jabbing a finger and visibly looping/parroting himself; a soft PEOPLE-PLEASER
caving with a tiny white flag; a BRILLIANT one calmly holding one long elegant
scroll, already finished. Generic blobs, no brand logos. [apply STYLE BIBLE +
CHARACTER SHEET]
```
中文：正中主角是个憨憨的温度旋钮，指针拨得很高，旁边的角色却平静又有创意（高温没事，不乱）；角落一个低档位画着一只僵硬的发条鹦鹉，死板复读。旋钮周围圆桌上三种 AI 性格：一个轴杠精戳着手指、明显在原地打转复读；一个老好人举着小白旗滑跪；一个聪明的家伙淡定地捧着一卷又长又漂亮的卷轴、早就写完了。用通用 blob，别带任何品牌 logo。

### 12 — 宪法功能随模型变强而迁移 / The Constitution's Role Migrates
```
Diptych of the same rulebook held by two students. LEFT: a clumsy student uses the
book as a TEXTBOOK / corrective crutch, propped up by it. RIGHT: a clever, slippery
student is gently but firmly handcuffed/anchored to a role-costume by the same book
— the book now functions as binding law, not a lesson. Smarter = needs welding into
its role more. [apply STYLE BIBLE]
```
中文：同一本规则书。左边笨学生把它当教科书/拐杖撑着；右边聪明又滑头的学生被这本书温和而坚定地"铐"在角色服装里。模型越聪明，宪法越像程序法而非教科书。

### 13 — 符号不是结论，刻度才是 / Magnitude, Not Sign
```
LEFT: a crude binary ON/OFF switch (flipped) — crude and dumb. RIGHT: a precise
analog dial/gauge with a needle, showing HOW FAR from a threshold line and an
arrow showing whether the gap is WIDENING or NARROWING. A character wisely reading
the dial, ignoring the dumb switch. [apply STYLE BIBLE]
```
中文：左边一个粗暴的开关（已拨动）；右边一个精密的模拟刻度盘，指针显示"离临界线多远"以及"在扩大还是收敛"的箭头。聪明角色看刻度，无视开关。

### 14 — 输入要审计：语义精确 + 消息溯源 / Audit the Inputs
```
The DATA OFFICER clerk at an intake desk inspecting paper slips. A relay/telephone-
game line behind: a tweet → a wire reporter → a data vendor → the dossier, the
message visibly FADING and shrinking at each hand-off. On the desk, the clerk uses
a magnifying glass to separate two stamps: one "FACT" icon, one "GUESS" icon (shown
as two distinct icon-stamps, no letters), refusing a slip that disguises a guess as
a fact. To one side, the clerk is also stepping out through a little door to fetch a
FRESH live witness on demand (live search) instead of trusting the faded relay.
[apply STYLE BIBLE + CHARACTER SHEET]
```
中文：Data Officer 在收件台审查纸条。背后是"传话游戏"接力：推文→记者→数据商→卷宗，消息每过一手就褪色、缩小。台上他用放大镜把"事实"章和"推测"章分开（用两个不同图标表示，不写字），拒收一张把推测伪装成事实的纸条。

### 15 — 复杂度是面罩，不是上限 / Complexity Is a Mask, Not a Ceiling
```
An elaborate ornate three-piece carnival costume (a fancy "options-combo" outfit)
hanging SEALED inside a glass case with a simple latch. In front of the case, a
plain trio of simple round buttons shown as three blank colored circles (BUY / HOLD
/ SELL, no text). The fancy power is sealed by choice, not by limit; the latch is
trivial to open. [apply STYLE BIBLE]
```
中文：一套华丽繁复的"三件套"嘉年华戏服被封在玻璃柜里（简单插销）；柜前只摆着三颗朴素圆钮（买/持/卖，用三个无字色块表示）。复杂能力是主动封印的，插销随手可开——但解封≠交付。

### 16 — 天经地义是跨界者的盲区 / The Blind Spot of the Obvious
```
A boundary-crosser character standing confidently on a bridge between two islands
(finance island and AI island), pointing at something it finds utterly OBVIOUS —
but the obvious thing is invisible to them (a transparent/ghosted shape) while the
audience on the other shore squints, unable to see it. What's obvious to you is
invisible to others. [apply STYLE BIBLE]
```
中文：跨界者站在连接"金融岛"和"AI 岛"的桥上，自信地指着一个他觉得理所当然的东西——可那东西对他自己是透明的（看不见），对岸的听众却怎么也看不清。你的天经地义，是别人的盲区。

---

## 备用：封面 / Optional Cover Image
```
A cozy round-table scene: ZEALOT (warm red), REAPER (cool blue) and FULCRUM (grey)
in lively debate around a small table; the CHRONICLER scribe sits just outside the
ring quietly transcribing with a quill. Above the table, a single steady gauge
needle points center despite the heated argument. Warm, witty, inviting. The whole
"stability from motion" thesis in one frame. [apply STYLE BIBLE + CHARACTER SHEET]
```
中文：圆桌场景——暖红 Zealot、冷蓝 Reaper、灰 Fulcrum 激烈辩论，Chronicler 抄写员在圈外安静记录；桌子上方一根指针在激辩中稳稳指向中位。一图概括"稳定来自动态"。
