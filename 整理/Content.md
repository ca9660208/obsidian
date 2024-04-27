---
aliases:
  - 內容
  - Contents
  - content
  - contents
---
# 內容 (Content)

[[Tag|標籤]]中間包圍的就是[[Element|元素]]的內容，可以是直接一段文字內容，也可以[[Nesting#巢狀元素 / 嵌套元素 (Nesting Element / Nested element)|巢狀元素]]下的內容。

```html
<!-- 內容 -->
<div>Content</div>
```

```html
<!-- 巢狀標籤狀態下的內容 -->
<div>
	<div>Content 1</div>
	<div>Content 2</div>
</div>
```

## 特殊符號

由於 [[HTML Introduction|HTML]] 是標記語言，並非純文字，因此無法正常顯示一些特殊字元或情況。例如：連續空格、`<tag>`或換行。

如果要使用，則必須使用對應的標記語言。例如：

- 使用 `&nbsp;`(Non-Breaking Space) 表示空白。
- `&lt;` 表示 `<`。
- `&gt;` 表示 `>`。
- `<br/>` 表示換行。

```html
<!-- Bad：連續空白 -->
<p>無法連續空白：空白開始.    空白結束</p>
<!-- Good：連續空白 -->
<p>連續空白：空白開始&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;空白結束</p>
```

```html
<!-- Bad：標籤符號 -->
<p>無法出現標籤：<span></p>
<!-- Good：標籤符號 -->
<p>出現標籤：&lt;span&gt;</p>
```

```html
<!-- Bad：換行 -->
<p>
	不能換行
	不能換行
</p>

<!-- Good：換行 -->
<p>
	可以換行
	<br/>
	可以換行
<p>
```