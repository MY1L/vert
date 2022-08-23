`vert`是竖排（vertical）的OT特性。

## 未来饼黑・Glow Monu
若干专用于竖排漫画嵌字字体，改自 Glow Sans SC

1. 自[Monu](https://github.com/MY1L/QuQi/releases)引入了一些常用漫符（如〰〰〰，⸻，♡，💔️），并调整字重以匹配。附漫符文本方便复制粘贴。
2. 制作了专门用于竖排的全角大写英文数字。同时这些也单独分拆为西文字体：[Ctrl Ordn](https://github.com/MY1L/Ctrl#ordn)
3. 若干标点为竖排而调整。
4. 给**缺乏连字功能**的嵌字软件添加统一码已有的连字标点：`‼` `⁇` `⁈` `⁉`
5. 在私用区补充了些统一码尚无的漫符和合字。

### 更新记录
- （前略）
- 2022-8-21 v0.93：未来饼黑之三：方书（Glow Monu Norm Book）初公开，字重接近雅黑常规，横排西文部分是Monu。

### 已知问题
1. 不同软件会在竖排时将不同的个别字符旋转90°，这导致我可能要专门针对某些软件预置旋转-90°字符。请在[这报错时](https://github.com/MY1L/vert/issues)说明你用的软件和版本。
2. 不考虑横排。不过横排除了个别标点间字距偏远外应该没什么问题。
3. 由于统一码没有“!!!”这种标点，我动用了私用区。你可以[在这提交](https://github.com/MY1L/vert/issues)提交更多漫符（要原漫画对应截屏）
4. 发现Adobe系软件可能对思源改.otf有支持问题，如果发现软件卡顿，请换.ttf。

### 未来计划
毕竟是`vert`，本系列字体的横排西文算是一塌糊涂——反正实际嵌字基本用不上。但我发现居然有拿来当横排字幕用的（还是不举例了），所以准备重做西文和横排度量。

下载和阅览漫符文本：[MY1L/vert/releases](https://github.com/MY1L/vert/releases)

## 未竟漫符・~Ctrl~ Msym
一组原创的 漫画<sup> **M**anhua </sup>符号<sup> **Sym**bol</sup> 字体。取名「未竟漫符」，是希望在软件的字体列表里与「未来饼黑」排到一起方便选择。
>其中许多线状漫符可以互相之间左右衔接无限连续。

>有些常见漫符不存在于统一码，比如“情绪渐强浪纹”啥的，这些放私用区和ASCII码位上方便复制粘贴。

### 更新记录
- 2021-4-1* v0：曾命名“Glow Monu Dash”，作为饼黑补充。
  - 我的老旧笔记本生成中文字体太慢，为了快捷地让饼黑支持更多线状漫符就单独分拆一个小字体。
- 2022-8-21 v1：初公开。此版RI合字放到U+F9AC`怜`的位置上。
- 2022-8-23 v2：解决先前已知问题。`～~〰`字形全部调整，这3个之间也可以任意混合连续。
  - 追加1个比例宽度连续波浪号(私用区)，1个SCP风格全角黑条`█`，1个圆体「未圆漫符」（仅常规字重）

### 已知问题
- 不太支持竖排。这可不`vert`

下载、例图、漫符文本：[MY1L/vert/releases/tag/Msym](https://github.com/MY1L/vert/releases/tag/Msym)
