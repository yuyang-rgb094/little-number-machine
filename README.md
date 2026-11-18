# Little Number Machine · 数字咔哒机

> A playful mechanical counter for exploring carrying, decimal points, and place value with young children.  
> 一台给孩子亲手操作的机械计数器，用来探索进位、小数点和数位的意义。

**Try it / 在线体验：** [Open the Little Number Machine](https://yuyang-rgb094.github.io/little-number-machine/)  
**Run locally / 本地使用：** Download this project and open `index.html` in a browser. No installation or internet connection is required.  
下载项目后，直接用浏览器打开 `index.html`，无需安装，也无需联网。

## Overview · 项目简介

**English**

Little Number Machine is a screen-based teaching toy originally designed for a three-year-old who already recognizes Arabic numerals. Instead of asking her to count objects or answer questions, it invites her to turn a mechanical counter and notice what changes.

The project follows a short learning path: a digit reaches 9 and carries into the next place; a decimal point separates whole cups from part of another cup; and the same digits represent different amounts when the decimal point moves.

**中文**

数字咔哒机最初是为一位已经认识阿拉伯数字的三岁孩子设计的屏幕教具。它不要求孩子数物品，也不通过答题来检验学习成果，而是让孩子亲手拨动机械计数器，观察数字和数量发生的变化。

教具由三个小游戏组成：个位走到 9 后向高位进位；小数点把完整的果汁杯和不到一杯的部分分开；数字保持不变时，移动小数点会改变所表示的数量。

## Background · 设计背景

**English**

Recognizing digits and understanding place value are different skills. A young child may comfortably read `9`, `10`, or `1.5` without yet knowing why `09` becomes `10`, or why `12.3` and `1.23` are different.

The design therefore starts with digital symbols rather than counting beads. It does not attempt to accelerate formal arithmetic instruction. Its purpose is to give a child a few memorable, hands-on experiences from which later ideas about place value can grow.

**中文**

认识数字与理解数位是两种不同的能力。孩子可能会读 `9`、`10` 或 `1.5`，却还不知道为什么 `09` 会变成 `10`，也不明白为什么 `12.3` 和 `1.23` 不一样。

因此，这个项目直接从孩子熟悉的数字符号出发，不再回到数珠子的阶段。它的目标不是提前教授正式运算，而是提供几次可以亲手操作、容易记住的体验，为以后理解数位打下基础。

## Teaching Principles · 教学理念

### 1. Direct manipulation before explanation · 先操作，再解释

**EN:** The child presses one button and watches the machine respond. An adult offers a short explanation only after the change is visible.  
**中：** 孩子先按按钮，观察机器的变化，大人再用一句简短的话解释，不让抽象讲解先于体验。

### 2. Change one thing at a time · 每次只改变一个关键条件

**EN:** During carrying, the digits change. In the decimal activity, the juice and the final digit change together. In the moving-point activity, the digits stay fixed while only the decimal point moves.  
**中：** 进位游戏关注数字牌的变化；小数游戏让果汁和最后一位数字同步变化；搬家游戏则保持数字不变，只移动小数点。

### 3. Connect symbols with familiar quantities · 把数字和熟悉的数量联系起来

**EN:** Whole and partial cups of juice make `1.5` visible as one full cup and half of another. Tree height provides a qualitative comparison when the decimal point moves.  
**中：** 用整杯和不到一杯的果汁，让 `1.5` 对应“一杯半”；用小树的高矮，直观比较小数点移动前后的数量大小。

### 4. Play without testing · 不考试，也不打分

**EN:** There are no scores, timers, failure states, or required repetitions. A child may explore freely, return to an earlier step, or stop at any time.  
**中：** 没有分数、计时、失败状态和规定次数。孩子可以自由尝试、倒回上一步，也可以随时结束。

### 5. Keep adult language small · 大人的解释保持简短

**EN:** Each screen includes an optional note for the adult. The goal is shared attention, not asking the child to repeat terminology.  
**中：** 每个页面都附有可选的家长提示。重点是共同观察，不要求孩子复述术语。

## Learning Path · 教学路径

### 01 · Carrying · 进位

**English**

The child advances the counter from `09` to `10`. The ones digit returns from 9 to 0 while the tens digit moves forward by one. Presets such as `19` and `99` make it easy to revisit the same pattern.

The intended discovery is: **when one digit reaches the end of its cycle, it returns to 0 and the digit on its left advances.**

**中文**

孩子把计数器从 `09` 拨到 `10`，看到个位从 9 回到 0，同时十位前进 1。也可以直接选择 `19` 或 `99`，反复观察同一规律。

希望孩子形成的直觉是：**某一位走到头以后回到 0，并请左边那一位向前走。**

**Suggested adult prompt / 家长可以说：**  
“9 走到头了，个位回到 0，左边前进 1。”  
“Nine is the end of this digit’s cycle. It returns to zero, and the digit on the left moves forward.”

### 02 · Decimal Point · 认识小数点

**English**

Adding a little juice changes `1.0` into `1.1`, then `1.2`. At `1.5`, the display shows one full cup and half of another. At `1.9`, one more step produces `2.0`, connecting decimal notation with the carrying pattern encountered earlier.

The intended discoveries are: **a decimal point is a position marker; `1.5` lies between 1 and 2; and carrying also works across the decimal point.**

**中文**

每加一次果汁，数字就从 `1.0` 变成 `1.1`、`1.2`。到 `1.5` 时，杯子呈现“一杯半”；从 `1.9` 再加一点会变成 `2.0`，把小数与前面见过的进位规律联系起来。

希望孩子形成的直觉是：**小数点是位置标记；`1.5` 在 1 和 2 之间；小数点后面也会发生进位。**

**Suggested adult prompt / 家长可以说：**  
“小数点左边是完整的杯数，右边是下一杯里的一点点。”  
“The digits on the left tell us the whole cups. The digit on the right tells us about part of another cup.”

### 03 · Moving Point · 点点搬家

**English**

The digits `1`, `2`, and `3` remain fixed while the decimal point moves through `123`, `12.3`, and `1.23`. A growing tree gives a qualitative sense of the changing amount.

The intended discovery is: **the same digits can represent different amounts when the decimal point changes position.**

**中文**

数字 `1`、`2`、`3` 始终不变，只让小数点在 `123`、`12.3` 和 `1.23` 之间移动，再用小树的高矮表示数量变化。

希望孩子形成的直觉是：**数字相同，小数点的位置不同，表示的数量也会不同。**

**Suggested adult prompt / 家长可以说：**  
“数字没有换，小数点搬家了。你猜小树会变高还是变矮？”  
“The digits stayed the same, but the point moved. Do you think the tree will grow or shrink?”

## Why a Mechanical Counter? · 为什么采用机械计数器？

**English**

A mechanical counter makes an abstract rule visible as a sequence of physical events. Its split-flap digits, central seam, screws, and click sounds give each action a clear beginning and end. When carrying occurs, more than one card flips, helping the child notice that the change travels from right to left.

The styling is functional rather than decorative: large digits support attention, the decimal point has its own color and label, and animation is reserved for meaningful state changes.

**中文**

机械计数器把抽象规则变成一连串看得见的事件。翻牌数字、中央接缝、螺丝和咔哒声，让每次操作都有清楚的开始和结束。发生进位时，不止一张牌翻动，孩子更容易注意到变化正在从右向左传递。

这些设计不只是装饰：大数字帮助孩子集中注意力，小数点使用独立的颜色和标签，动画只用于表现真正发生的变化。

## Teaching Mode · 亲子共玩模式

**English**

The intended format is short adult-child co-play, usually one or two minutes per activity. The child operates the machine; the adult watches, asks an occasional prediction question, and names what happened. There is no need to complete all three activities in one sitting.

A simple rhythm is:

1. **Operate:** let the child press the button.
2. **Observe:** wait for the cards, cups, or tree to finish changing.
3. **Describe:** offer one short sentence about the change.
4. **Repeat or stop:** follow the child's interest rather than a lesson plan.

**中文**

推荐使用亲子共玩的方式，每个小游戏持续一两分钟即可。孩子负责操作，大人负责陪伴观察，偶尔让她猜一猜接下来会怎样，再用一句话描述已经发生的变化。不需要一次完成三个游戏。

可以遵循这样的节奏：

1. **操作：** 让孩子自己按按钮。
2. **观察：** 等数字牌、果汁杯或小树完成变化。
3. **描述：** 用一句简短的话说出刚才发生了什么。
4. **重复或结束：** 跟随孩子的兴趣，不必追赶教学进度。

## Scope and Boundaries · 教学边界

**English**

“Moving Point” is an early intuition activity about decimal-point position and magnitude. It is **not** a lesson about binary floating-point representation, IEEE 754, significant bits, exponents, or numerical approximation. Likewise, the juice and tree graphics are conceptual aids, not precise measuring instruments.

The project is a teaching toy, not an assessment tool or a substitute for a structured mathematics curriculum.

**中文**

“点点搬家”讲的是小数点位置与数量大小的早期直觉，**并不是**计算机科学中的浮点数课程，不涉及二进制表示、IEEE 754、有效位、阶码或数值误差。果汁杯和小树也是帮助理解的示意图，并非精确的测量工具。

这个项目是亲子教具，不是测评工具，也不能替代系统的数学课程。

## Features · 功能特点

- **Three focused activities:** carrying, decimal notation, and moving the decimal point.  
  **三个专注的小游戏：** 进位、小数表示和小数点搬家。
- **Mechanical feedback:** split-flap animation and synthesized click sounds.  
  **机械反馈：** 翻牌动画和程序生成的咔哒声。
- **Optional Chinese narration:** uses the device's built-in speech synthesis when available.  
  **可选中文朗读：** 在设备支持时使用系统自带语音。
- **Offline and private:** no external libraries, analytics, accounts, or data collection.  
  **离线且注重隐私：** 无外部依赖、统计分析、账号或数据收集。
- **Responsive and accessible:** supports mobile layouts, keyboard-operated tabs, visible focus states, and reduced-motion preferences.  
  **适配与无障碍：** 支持手机布局、键盘切换标签、清晰的焦点状态和减少动态效果偏好。

## Quick Start · 快速开始

### Open directly · 直接打开

1. Download or clone this repository.  
   下载或克隆本仓库。
2. Open `index.html` in Safari, Chrome, Edge, or another modern browser.  
   使用 Safari、Chrome、Edge 或其他现代浏览器打开 `index.html`。
3. Choose an activity and let the child operate the main button.  
   选择一个小游戏，让孩子操作主按钮。

There is no build step, package manager, server, or API key.  
无需构建、安装依赖、启动服务器或配置 API Key。

### Optional local server · 可选的本地服务器

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.  
然后访问 `http://localhost:8000`。

## Project Structure · 项目结构

```text
little-number-machine/
├── index.html   # Complete standalone teaching toy / 完整的单文件教具
└── README.md    # Bilingual project and teaching guide / 英中对照项目与教学说明
```

## Technology · 技术实现

**EN:** Semantic HTML, custom CSS, and vanilla JavaScript. The project uses the Web Audio API for mechanical clicks and Speech Synthesis for optional narration, with graceful fallback when either is unavailable.  
**中：** 使用语义化 HTML、自定义 CSS 和原生 JavaScript；通过 Web Audio API 生成机械声，通过 Speech Synthesis 提供可选朗读，设备不支持时仍可正常操作。

---

Made for curious little observers and the adults who play beside them.  
送给好奇的小小观察员，以及陪他们一起发现的大人。
