---
aliases:
  - character
  - characters
  - Characters
  - 字元
---
# 字元 (Character)

電腦或是[[Browser|瀏覽器]]等要能夠正確顯示字元必須知道他是如何「編碼 (encoding)」的。

通常會將所有的字元集合，稱為「字元集 (Character Sets)」。

大部分現代電腦預設編碼都為 [[UTF-8]] 字元集。其他編碼還有：[[ASCII]]、[[Windows-1252]] (ANSI)、[[ISO-8859]]...等。

| 版本預設   | 編碼            |
| ------ | ------------- |
| HTML 4 | ISO-8859-1    |
| HTML 5 | Unicode UTF-8 |

_所有 HTML5 和 XML 處理器都支援 [[UTF-8]]、UTF-16、Windows-1252 和 ISO-8859。_

_UTF-8 的前 128 個字元與 [[ASCII]] 具有相同的二進位值，使 [[ASCII]] 文字成為有效的 [[UTF-8]]。_

## 瀏覽器切換編碼

要使用非預設 [[UTF-8]] 的編碼，可以指定 metadata 切換。

```html
<meta charset="ISO-8859-1">
```

## Difference Between Unicode and UTF-8

Unicode 是一種字元集。它將字元轉換為十進制的數字。轉換成十進制的字元集對應表值。例如："hello" 將換成將被轉換成十進制的"104 101 108 108 111"。

UTF-8 是一種編碼。將數字轉換為二進制。轉換成二進制的電腦儲存格式。例如："hello" 將換成將被轉換成十進制的"01101000 01100101 01101100 01101100 01101111"。