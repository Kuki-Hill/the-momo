# Slide 02–04 研究缺口清单（Research Gaps to Verify）

> 本文件列出：目前的信息**还不足以**支撑 Slide 02–04（Pain is unavoidable / Pain care is fragmented / The Pain Moment / How Big Is the Problem）的哪些论证点，为什么不够，以及建议的下一步检索方向。**每一条都配了一段可以直接复制粘贴去发起 scite 检索的中文 prompt**，团队成员或下一次会话可以直接用。
>
> This file lists which claims in Slide 02–04 are **not yet sufficiently supported**, why, and what to search next. **Each gap includes a ready-to-copy Chinese prompt** for launching the next scite search.
>
> 配套文件 / Companion file：`02-03-04_Problem-Raw-Info-For-Review.md`

---

## 1. 两大目标疼痛场景完全没有患病率数据 / No prevalence data for 2 of the 3 target pain scenarios

**状态 / Status：✅ 已解决（2026-09-11）** — 检索完成，证据已并入 `02-03-04_Problem-Raw-Info-For-Review.md` 新增的 **B2 节**。核心可用数字：
- 中国偏头痛 6.1%、紧张型头痛 13.4%，且 2000–2023 年较 1988–1999 年明显上升（Zhang 2025）
- 全球大学生偏头痛 19%，女性 23%、亚洲 16%（Flynn 2022，最贴近产品目标人群）
- 全球功能性消化不良 FD 8.4%（Rome IV 6.8%）（Kwon 2024，44 研究/40 国）
- 全球肠易激综合征 IBS：Rome III 9.2% vs Rome IV 3.8%，女性 12.0% vs 男性 8.6%（Oka 2020, Lancet Gastro Hepatol）

**两个引用注意点**：
1. Oka 2020 有一条 2020-12 erratum，已核实——修正的是某亚型图的 I² 统计量，不影响 Rome III 9.2% / Rome IV 3.8% / 性别比等主结果，可安全引用主结果（B2 节有详细说明）。
2. **香港本地的头痛/功能性腹痛患病率调查未找到**，香港数字仍是缺口（与缺口 6 相关）。Slide 04 如需香港数字，这两类疼痛需借用中国全国或全球数据，或明确标注"香港本地数据暂缺"。

---

## 2. "Pain care is fragmented" 核心论点没有文献支撑 / "Care is fragmented" has zero direct evidence

**状态 / Status：✅ 已解决（2026-09-11）** — 检索完成，证据已并入 `02-03-04_Problem-Raw-Info-For-Review.md` 新增的 **F 节**。核心可用数字：
- 纤维肌痛：确诊前平均 2.3 年、看 3.7 位医生（Choy 2010）
- 原发性头痛：28.5% 初诊无法确诊，40% 以上患者 3–5 年内被改诊断（Tatsuno 2025，日本全国 33.7 万理赔数据）
- 子宫内膜异位症：平均确诊延迟 10 年，青少年中位看 3 位医生（Breton 2025; Dun 2015）
- 术后 doctor shopping 患病率 20.8%（Morris 2014）

**对 Slide 02 措辞的建议**：现有证据支撑的是"确诊前辗转多医生/长期误诊/重复检查"这一具体现象，而不是抽象的"care coordination 失败"。建议 slide 02 用这些具体数字来讲，避免直接说 "care is fragmented" 这种没有单一文献直接测量的宏观论断。

---

## 3. 年龄段情绪/心理共病检索未完成 / Age-segmented psychological comorbidity search was interrupted

**缺口**：上一轮会话检索"不同年龄段长期疼痛/痛经的情绪心理共病"时，在读取搜索结果的过程中被 API 报错（ECONNRESET）中断。只有候选文献标题（如 Dudeney et al., 2024, JAMA Pediatrics, DOI 10.1001/jamapediatrics.2024.3039），从未读摘要、从未查是否撤稿、从未整理出具体数字。

**为什么不够**：这一块目前完全不能出现在 deck 里——不是"证据弱"，是"根本没有验证过"。

**建议方向**：完成被中断的检索：核实候选 DOI 是否可用，补齐青少年/成人/老年三个年龄段的抑郁/焦虑共病数据。

**建议 prompt**：
```
继续之前被中断的检索：请用 scite 核实 DOI 10.1001/jamapediatrics.2024.3039
（Dudeney et al., 2024, JAMA Pediatrics，青少年慢性疼痛与抑郁/焦虑）是否存在
撤稿/更正通知，并读取其摘要给出具体患病率数字；同时补充检索老年慢性疼痛与抑郁
共病、以及痛经与 catastrophizing/somatization/quality of life 的文献，按年龄段
（青少年/成人/老年）分别整理患病率或效应量数字，附 DOI。
```

---

## 4. "Hard to track in the moment" 目前只是团队假设 / "Hard to track" is currently just an assumption

**状态 / Status：✅ 已解决（2026-09-11）** — 检索完成，证据已并入 `02-03-04_Problem-Raw-Info-For-Review.md` 新增的 **E 节**。核心可用数字：
- 纸日记自报依从率 90% vs 实际 11%（Stone 2002, BMJ）
- 纸日记 0% 缺失背后 42% 患者事后补填造假（Gaertner 2004）
- 高频"当下"提示完成率仅 63.3%（Joo 2024）
- 降低交互负担（μEMA 微交互）显著提高应答率（Ponnada 2017）
- 事后回忆受 peak-end 偏差影响、系统性高估（Stone 2005; Schneider 2011; Van den Bergh 2016）

**注意**：Gaertner 2004 关联的 2004 年 erratum（DOI 10.1016/j.jpainsymman.2004.11.004）已核实——内容是同刊另一篇过敏测试文章的表格修正，与本篇数字无关，可以安全引用。

---

## 5. 工作/学习/生产力损失数据缺失 / Missing work/productivity impact data

**缺口**：原始产品构思文档（§2.1）明确列出了"疼痛对工作、学习和睡眠的影响""因疼痛造成的缺勤和生产力损失"作为要收集的数据方向，但两轮检索都没有真正搜索这个方向。

**为什么不够**：这类数据通常是投资人/评委最容易理解、最有说服力的"问题有多严重"证据（经济损失比患病率百分比更直观），目前完全空缺。

**建议方向**：presenteeism / absenteeism / work productivity loss，针对 chronic pain / migraine / dysmenorrhea，全球+中国/香港数据。

**建议 prompt**：
```
帮我用 scite 检索慢性疼痛/头痛/痛经对工作出勤和生产力的影响，关键词方向包括
presenteeism、absenteeism、work productivity loss chronic pain/migraine/
dysmenorrhea、economic burden，全球和中国/香港数据都要，附具体天数或经济损失
数字和 DOI。
```

---

## 6. 香港本地数据偏旧 / Hong Kong data may be outdated

**缺口**：现有香港数字最新是 2016 年（慢性疼痛趋势）、2018 年（痛经，中学生）；基础数字 Ng et al. 是 2002 年（24 年前）、Wong & Fielding 是 2011 年（15 年前）。没有任何 2020 年之后的香港本地患病率数据。

**为什么不够**：pitch 面向的是投资人/评委，用十几二十年前的数字讲"现在的问题有多大"容易被质疑数据时效性。

**建议方向**：搜索是否有 2020 年后的香港本地患病率更新调查；如果确实没有，也要明确知道"目前最新数据就是 2016/2018 年"这一事实，以便在 pitch 里做好措辞（比如强调趋势而非具体年份）。

**建议 prompt**：
```
帮我用 scite 检索 2020 年以后发表、针对香港人群的慢性疼痛或痛经患病率调查，
关键词方向包括 Hong Kong chronic pain prevalence 2020/2021/2022/2023/2024、
Hong Kong dysmenorrhea survey recent，如果没有 2020 年后的本地数据，明确告诉
我目前最新的香港数据年份是哪一年。
```

---

## 7. 部分 DOI 标注 2026 年发表，需要二次核实 / Some 2026-dated DOIs need re-verification

**缺口**：现有引用中有 Heapy et al., 2026（JAMA, DOI 10.1001/jama.2026.7861）、Singh et al., 2026（Indian J Med Res, DOI 10.25259/ijmr_1935_2025）。虽然现在确实是 2026-09，这类文献理论上可能已经 in-press/早发表，但"卷号/年份看起来很新"本身是一个需要多留意核实的信号，不能假设检索工具一定没有出错。

**为什么不够**：如果最终引用了一个无法解析或元数据有误的 DOI，会直接影响 pitch 的可信度和团队的学术诚信。

**建议方向**：逐一用 scite 重新解析这些 DOI，确认真实存在、无撤稿/更正通知。

**建议 prompt**：
```
请用 scite 逐一核实以下 DOI 是否真实存在、可解析、且没有撤稿/更正通知：
10.1001/jama.2026.7861（Heapy et al., 2026）、10.25259/ijmr_1935_2025
（Singh et al., 2026）。如果解析不到或元数据异常，明确告诉我，不要沿用
之前的引用。
```

---

## 8. 数字疼痛干预综述与 Problem 部分的关系不明确 / Unclear where the digital-intervention review belongs

**缺口**：第一轮检索（App/VR/严肃游戏/CBT 数字疼痛干预效果，见清单 C 类）更像是"现有产品方案效果如何"的证据，适合放在 Slide 05 Existing Solutions 或 Slide 07–09 Solution 部分，而不是 Problem 部分。目前没有人明确决定这批引用归属哪一页。

**为什么不够**：不是证据本身有问题，而是有被**遗漏**或**重复使用**的风险——如果 Problem 组和 Solution 组各自不知道对方在用什么引用，容易出现内容对不上或重复的情况。

**建议方向**：这不是新检索，是团队内部的归属讨论。

**建议 prompt（团队讨论用，非检索）**：
```
在 9/14 团队会议上确认：数字疼痛干预文献综述（Heapy 2026 CBT-CP、Sinha 2022
Wysa、Saragih 2024 严重游戏、Richardson 2020 儿科 mHealth）具体用在 Slide 05
Existing Solutions 还是 Slide 07-09 Solution 部分，避免和 Problem 部分的引用
重复或遗漏。
```

---

## 优先级建议 / Suggested priority

若时间有限（Sept 13 前需要交出 Problem/Market 初稿），建议优先处理：
1. ~~缺口 1（migraine/胃痛患病率）~~ — **已完成 2026-09-11**，证据见清单 B2 节（注意：香港本地头痛/胃痛数据仍缺，与缺口 6 合并处理）
2. ~~缺口 4（hard to track 的证据）~~ — **已完成 2026-09-11**，证据见清单 E 节
3. ~~缺口 2（care fragmented 证据）~~ — **已完成 2026-09-11**，证据见清单 F 节
其余（3、5、6、7、8）可以在 Sept 14 团队会议后视时间决定是否补做。三大 P0 缺口已全部关闭，Slide 02–04 的核心论点现在都有文献支撑。
