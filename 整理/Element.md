---
aliases:
  - 元素
  - Elements
  - element
  - elements
---
# 元素 (Element)

## 基本元素

[[HTML Introduction|HTML]] 最小的組成單元。

元素主要是透過[[Tag|標籤]]組成，由「起始標籤 (Opening tag)」到「結束標籤 (Closing tag)」的所有內容稱之為元素。

元素包含了[[Tag|標籤]]、[[Content|內容]]與[[Attribute|屬性]]。

- [[Tag|標籤]] ：能夠表達出元素結構語意。例如：`<p>` 表示段落 (paragraph)。
- [[Attribute|屬性]] ：元素的樣式或功能。
- [[Content|內容]] ：元素的內容，可以是文字，或是更多的元素結構。

### A Simple Sample

| 起始標籤  | 內容                  | 結束標籤   |
| ----- | ------------------- | ------ |
| `<p>` | My first paragraph. | `</p>` |

```html
<p>My first paragraph.</p>
```

## 空元素 / 自閉合標籤 (Empty Element /  Void Element / Self-closing Tag)

有些 [[HTML Introduction|HTML]] 元素是不允許有[[Content|內容]]的，我們稱之為空元素。

```html
<img src="images/firefox-icon.png" alt="My test image" />
```

有些特殊[[Tag|標籤]]可以不用結束標籤 。例如：`<br>` 換行符號。_雖然有效，但推薦需要結束標籤關閉元素保持統一及長期有效。_

## Suggest

### HTML is Not Case Sensitive

The [[HTML Introduction|HTML]] standard does not require lowercase [[Tag|tags]], but [[World Wide Web Consortium|W3C]] **recommends** lowercase in HTML, and **demands** lowercase for stricter document types like XHTML.