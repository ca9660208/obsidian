---
aliases:
  - color
  - colors
  - Colors
  - 顏色
---
# 顏色 (Color)

[[HTML Introduction|HTML]] 的顏色可以使用多種狀態值來表示。

- 預先定義的「[[#Color Names|顏色名稱 (Color Names)]]」。
- [[#RGB Color Values|RGB 值]]。
- [[#RGBA Color Values|RGBA 值]]。
- [[#HEX Color Values|HEX 值]]。
- [[#HSL Color Values|HSL 值]]。
- [[#HSLA Color Values|HSLA 值]]。

## RGB Color Values

RGB  顏色值透過以下方式指定：`rgb(red, green, blue)`。

- `red`(紅色)：定義紅色顏色的強度，其值介於 `0` 到 `255` 之間。
- `green`(綠色)：定義綠色顏色的強度，其值介於 `0` 到 `255` 之間。
- `blue`(藍色)：定義藍色顏色的強度，其值介於 `0` 到 `255` 之間。

_意味著有 256 x 256 x 256 = 16777216 種可能的顏色！_

## RGBA Color Values

RGBA 顏色值是具有 Alpha 選項的 RGB 顏色值的擴展 - 用於指定顏色的不透明度。

RGBA 顏色值透過以下方式指定：`rgba(red, green, blue, alpha)`。

- `red`(紅色)：定義顏色的強度，其值介於 `0` 到 `255` 之間。
- `green`(綠色)：定義顏色的強度，其值介於 `0` 到 `255` 之間。
- `blue`(藍色)：定義顏色的強度，其值介於 `0` 到 `255` 之間。
- `alpha`：定義顏色的不透明度，其值介於 `0.0`(完全透明)和 `1.0`(完全不透明)之間。

## HEX Color Values

十六進位顏色透過以下方式指定：`#RRGGBB`。

- `RR`(紅色)：十六進位整數指定紅色顏色的組成部分，其值介於 `00` 到 `ff` 之間的十六進位值。
- `GG`(綠色)：十六進位整數指定綠色顏色的組成部分，其值介於 `00` 到 `ff` 之間的十六進位值。
- `BB`(藍色)：十六進位整數指定藍色顏色的組成部分，其值介於 `00` 到 `ff` 之間的十六進位值。

_十六進位 `00` 到 `ff` 之值與十進位 `0` 到 `255` 相同。_

_可寫成 `#RGB` 三位數，等同於 `#RRGGBB`。_

_HEX Color 可擴展透明度，透過以下方式指定 `#RRGGBBAA`。`AA` 為十六進制的透明度值。_

## HSL Color Values

HSL  顏色值透過以下方式指定：`hsl(hue, saturation, lightness)`。

- `hue`(色調)：定義色調，其值介於色輪上 `0` 到 `360` 之間的度數。_`0` 是紅色，`120` 是綠色，`240` 是藍色。_
- `saturation`(飽和度)：定義飽和度，其值介於 `0%` 到 `100%` 之間的百分比值。_`0%` 表示灰度，`100%` 表示全色。_
- `lightness`(亮度)：定義亮度，其值介於 `0` 到 `255` 之間的百分比值。_`0%` 為黑色，`100%` 為白色。_

## HSLA Color Values

HSLA 顏色值是具有 Alpha 選項的 HSL 顏色值的擴展 - 用於指定顏色的不透明度。

HSL  顏色值透過以下方式指定：`hsl(hue, saturation, lightness, alpha)`。

- `hue`(色調)：定義色調，其值介於色輪上 `0` 到 `360` 之間的度數。_`0` 是紅色，`120` 是綠色，`240` 是藍色。_
- `saturation`(飽和度)：定義飽和度，其值介於 `0%` 到 `100%` 之間的百分比值。_`0%` 表示灰度，`100%` 表示全色。_
- `lightness`(亮度)：定義亮度，其值介於 `0` 到 `255` 之間的百分比值。_`0%` 為黑色，`100%` 為白色。_
- `alpha`：定義顏色的不透明度，其值介於 `0.0`(完全透明)和 1.0(完全不透明)之間。

## Color Names

Color Names | HEX Value
--- | ---
AliceBlue | `#F0F8FF`
AntiqueWhite | `#FAEBD7`
Aqua | `#00FFFF`
Aquamarine | `#7FFFD4`
Azure | `#F0FFFF`
Beige | `#F5F5DC`
Bisque | `#FFE4C4`
Black | `#000000`
BlanchedAlmond | `#FFEBCD`
Blue | `#0000FF`
BlueViolet | `#8A2BE2`
Brown | `#A52A2A`
BurlyWood | `#DEB887`
CadetBlue | `#5F9EA0`
Chartreuse | `#7FFF00`
Chocolate | `#D2691E`
Coral | `#FF7F50`
CornflowerBlue | `#6495ED`
Cornsilk | `#FFF8DC`
Crimson | `#DC143C`
Cyan | `#00FFFF`
DarkBlue | `#00008B`
DarkCyan | `#008B8B`
DarkGoldenRod | `#B8860B`
DarkGray | `#A9A9A9`
DarkGrey | `#A9A9A9`
DarkGreen | `#006400`
DarkKhaki | `#BDB76B`
DarkMagenta | `#8B008B`
DarkOliveGreen | `#556B2F`
DarkOrange | `#FF8C00`
DarkOrchid | `#9932CC`
DarkRed | `#8B0000`
DarkSalmon | `#E9967A`
DarkSeaGreen | `#8FBC8F`
DarkSlateBlue | `#483D8B`
DarkSlateGray | `#2F4F4F`
DarkSlateGrey | `#2F4F4F`
DarkTurquoise | `#00CED1`
DarkViolet | `#9400D3`
DeepPink | `#FF1493`
DeepSkyBlue | `#00BFFF`
DimGray | `#696969`
DimGrey | `#696969`
DodgerBlue | `#1E90FF`
FireBrick | `#B22222`
FloralWhite | `#FFFAF0`
ForestGreen | `#228B22`
Fuchsia | `#FF00FF`
Gainsboro | `#DCDCDC`
GhostWhite | `#F8F8FF`
Gold | `#FFD700`
GoldenRod | `#DAA520`
Gray | `#808080`
Grey | `#808080`
Green | `#008000`
GreenYellow | `#ADFF2F`
HoneyDew | `#F0FFF0`
HotPink | `#FF69B4`
IndianRed | `#CD5C5C`
Indigo | `#4B0082`
Ivory | `#FFFFF0`
Khaki | `#F0E68C`
Lavender | `#E6E6FA`
LavenderBlush | `#FFF0F5`
LawnGreen | `#7CFC00`
LemonChiffon | `#FFFACD`
LightBlue | `#ADD8E6`
LightCoral | `#F08080`
LightCyan | `#E0FFFF`
LightGoldenRodYellow | `#FAFAD2`
LightGray | `#D3D3D3`
LightGrey | `#D3D3D3`
LightGreen | `#90EE90`
LightPink | `#FFB6C1`
LightSalmon | `#FFA07A`
LightSeaGreen | `#20B2AA`
LightSkyBlue | `#87CEFA`
LightSlateGray | `#778899`
LightSlateGrey | `#778899`
LightSteelBlue | `#B0C4DE`
LightYellow | `#FFFFE0`
Lime | `#00FF00`
LimeGreen | `#32CD32`
Linen | `#FAF0E6`
Magenta | `#FF00FF`
Maroon | `#800000`
MediumAquaMarine | `#66CDAA`
MediumBlue | `#0000CD`
MediumOrchid | `#BA55D3`
MediumPurple | `#9370DB`
MediumSeaGreen | `#3CB371`
MediumSlateBlue | `#7B68EE`
MediumSpringGreen | `#00FA9A`
MediumTurquoise | `#48D1CC`
MediumVioletRed | `#C71585`
MidnightBlue | `#191970`
MintCream | `#F5FFFA`
MistyRose | `#FFE4E1`
Moccasin | `#FFE4B5`
NavajoWhite | `#FFDEAD`
Navy | `#000080`
OldLace | `#FDF5E6`
Olive | `#808000`
OliveDrab | `#6B8E23`
Orange | `#FFA500`
OrangeRed | `#FF4500`
Orchid | `#DA70D6`
PaleGoldenRod | `#EEE8AA`
PaleGreen | `#98FB98`
PaleTurquoise | `#AFEEEE`
PaleVioletRed | `#DB7093`
PapayaWhip | `#FFEFD5`
PeachPuff | `#FFDAB9`
Peru | `#CD853F`
Pink | `#FFC0CB`
Plum | `#DDA0DD`
PowderBlue | `#B0E0E6`
Purple | `#800080`
RebeccaPurple | `#663399`
Red | `#FF0000`
RosyBrown | `#BC8F8F`
RoyalBlue | `#4169E1`
SaddleBrown | `#8B4513`
Salmon | `#FA8072`
SandyBrown | `#F4A460`
SeaGreen | `#2E8B57`
SeaShell | `#FFF5EE`
Sienna | `#A0522D`
Silver | `#C0C0C0`
SkyBlue | `#87CEEB`
SlateBlue | `#6A5ACD`
SlateGray | `#708090`
SlateGrey | `#708090`
Snow | `#FFFAFA`
SpringGreen | `#00FF7F`
SteelBlue | `#4682B4`
Tan | `#D2B48C`
Teal | `#008080`
Thistle | `#D8BFD8`
Tomato | `#FF6347`
Turquoise | `#40E0D0`
Violet | `#EE82EE`
Wheat | `#F5DEB3`
White | `#FFFFFF`
WhiteSmoke | `#F5F5F5`
Yellow | `#FFFF00`
YellowGreen | `#9ACD32`