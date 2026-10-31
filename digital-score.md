---
id: digital-score
site: hist
cat: H3
title: 数字时代的乐谱
title_en: The Score in the Digital Age
summary: 软件、MIDI 与平板，如何改变乐谱的写作与阅读。
summary_en: Software, MIDI and tablets changed how scores are written, read and played.
level: standard
tags: [音乐史, 数字乐谱, MIDI, 排版]
tags_en: [music history, digital score, MIDI, engraving]
alias: [数字乐谱, 电子乐谱, 电脑乐谱, digital score, digital notation]
links:
  - "[[period:contemporary]]"
  - "[[glossary:daw]]"
  - "[[glossary:score]]"
  - "[[instrument:midi-controller]]"
instances:
  - mutopia-001093 | 《Maple Leaf Rag》的 Mutopia 版本由 LilyPond 源文件排版，谱面本身是可编译的文本
  - openscore-000025 | 《晨曲》的 OpenScore 数字转录，公共领域乐谱被转成可编辑、可交换的数据
  - atepp-002441 | 《哥德堡变奏曲》的演奏被录成 MIDI 事件，音符、时值与力度都成为可编辑的数据
sources:
  - The New Grove Dictionary of Music and Musicians, 2nd ed., entry "Computers and music".
  - Nicholas Cook, Beyond the Score (Oxford University Press).
updated: 2026-10-28
---

::: zh
## 问题

纸谱把音符、文字与版面固定在同一张纸上，数字谱把这三层拆开：排版文件负责外观，MIDI 负责声音，元数据负责版本与授权。乐谱因此可以搜索、转调、播放，也可能被复制到失去出处。

## 历史脉络

1970年代，计算机进入音乐排版，SCORE 与后来的 Finale、Sibelius、LilyPond 让作曲家排谱。1983年，MIDI 协议让键盘、合成器与电脑说同一种语言，演奏可被录成事件，再编辑、量化、回放。1990年代，网络让乐谱扫描与共享成为日常；Mutopia、IMSLP 与 OpenScore 把公共领域作品转成可编辑的数字文本。2010年代以后，MusicXML 与 MEI 让不同软件交换乐谱。

## 关键转折

第一次转折是分离。谱面与声音被拆成两套数据，排版文件负责看，MIDI 负责听。第二次转折是可编辑的演奏。MIDI 与音频工作站让演奏可被量化、移调、修补。第三次转折是屏幕上的谱。平板与同步谱让乐谱成为跟着音乐走的时间轴。

## 听什么

先听 Mutopia 排版的《Maple Leaf Rag》，源文件是纯文本，却能编译成标准谱面；再听 OpenScore 的《晨曲》，数字转录把1904年的公共领域歌曲变成可编辑文本；最后听一段演奏 MIDI，时值、力度与踏板都写成数字，编辑它就像编辑代码。库中版本多为合成音色，注意谱面与演奏的分离。

```audiolab
{"type":"instrument","gm":"Acoustic Grand Piano","synth":"struck","phrase":["C4","E4","G4","C5","G4","E4","C4"],"label":"同一份谱：既能排版，也能即时发声","label_en":"One score, engraved and sounded at once","hint":"听这四个音被平均地奏出，再想象它们同时作为谱面符号与 MIDI 事件存在","hint_en":"Hear the four notes played evenly, then imagine them existing as both page symbols and MIDI events"}
```

## 相关

数字谱属于[[period:contemporary]]，工具见[[glossary:daw]]与[[glossary:score]]，输入设备落到[[instrument:midi-controller]]。
:::

::: en
## The question

A paper score fixes notes, text and layout on one surface. A digital score separates these layers. The engraving file governs appearance, MIDI governs sound, and metadata governs version and rights. Once separated, a score can be searched, transposed and played, but it can also be copied until its source is lost.

## Historical arc

In the 1970s computers entered music engraving, and SCORE, later Finale, Sibelius and LilyPond let composers set pages. In 1983 MIDI gave keyboards, synths and computers one language, so performance could be recorded as events and then edited, quantised and replayed. In the 1990s the web made score scanning and sharing ordinary; Mutopia, IMSLP and OpenScore turned public-domain works into editable digital texts. After 2010, MusicXML and MEI let programs exchange scores.

## The turning point

The first turn was separation. Page and sound became two data sets, one for looking and one for hearing. The second turn was the editable performance. MIDI and the DAW allowed a take to be quantised, transposed and patched. The third turn was the score on screen. Tablets and synchronised scores turned the page into a timeline that moves with the music.

## What to listen for

Begin with the Mutopia edition of Maple Leaf Rag, whose plain-text source compiles into a standard page. Then hear OpenScore's Mattinata, a digital transcription of a 1904 public-domain song. Finally hear a performance MIDI, where duration, velocity and pedal are written as numbers, so editing it feels like editing code. The library versions are mostly synthesised, so notice the split between page and performance.

```audiolab
{"type":"instrument","gm":"Acoustic Grand Piano","synth":"struck","phrase":["C4","E4","G4","C5","G4","E4","C4"],"label":"One score, engraved and sounded at once","label_en":"One score, engraved and sounded at once","hint":"Hear the four notes played evenly, then imagine them existing as both page symbols and MIDI events","hint_en":"Hear the four notes played evenly, then imagine them existing as both page symbols and MIDI events"}
```

## Related

The digital score belongs to [[period:contemporary]], with [[glossary:daw]], [[glossary:score]] and [[instrument:midi-controller]].
:::
