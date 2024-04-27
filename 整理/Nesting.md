---
aliases:
  - 巢狀
  - 嵌套
  - Nest
  - nest
  - nesting
---
# 巢狀 / 嵌套 (Nest)

## 巢狀元素 / 嵌套元素 (Nesting Element / Nested element)

遵循巢狀結構寫的元素為巢狀元素。

[[Tag|標籤]]撰寫必須環狀包覆且完整閉合並對稱。

```html
<!-- 最小元素 -->
<div class="styles">content</div>

<!-- 巢狀元素 -->
<div class="wrapper">
	<h1 class="title">title</h1>
	<div class="content">content</div>
</div>

<!-- 非環狀包覆，錯誤寫法 -->
<div class="wrapper">
	<h1 class="title">
	<div class="content">
	</h1>
	</div>
</div>
```

```
正確

<html>
    <head>
    </head>
    <body>
    </body>
</html>

┌─────────┐
│ <html>  ├───┐
└─────────┘   │
┌─────────┐   │
│ <head>  ├─┐ │
└─────────┘ │ │
┌─────────┐ │ │
│ </head> ├─┘ │
└─────────┘   │
┌─────────┐   │
│ <body>  ├─┐ │
└─────────┘ │ │
┌─────────┐ │ │
│ </body> ├─┘ │
└─────────┘   │
┌─────────┐   │
│ </html> ├───┘
└─────────┘

錯誤

<html>
    <head>
    <body>
    </head>
    </body>
</html>

┌─────────┐
│ <html>  ├─────┐
└─────────┘     │
┌─────────┐     │
│ <head>  ├─┐   │
└─────────┘ │   │
┌─────────┐ │   │
│ <body>  ├─┼─┐ │
└─────────┘ │ │ │
┌─────────┐ │ │ │
│ </head> ├─┘ │ │
└─────────┘   │ │
┌─────────┐   │ │
│ </body> ├───┘ │
└─────────┘     │
┌─────────┐     │
│ </html> ├─────┘
└─────────┘
```

## Suggest

### 可讀性

根據巢狀結構，將不同層級元素分行以及「縮排 (indent)」，能增加格式碼的可讀性 。

```html
<!-- Good -->
<body>
	<p class="content">hello world<p>
	<ul>
		<li>清單 1</li>
		<li>清單 2</li>
	</ul>
</body>

<!-- Bad -->
<body>
<p class="content">hello world<p>
<ul><li>清單 1</li><li>清單 2</li></ul>
</body>
```