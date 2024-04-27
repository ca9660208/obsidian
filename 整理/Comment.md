---
aliases:
  - 註解
  - Comments
  - comment
  - comments
---
# 註解 (Comment)

## 作用

註解的內容「不會被顯示和執行的內容」。寫在註解裡註解區塊內的文字會被[[Browser|瀏覽器]]忽略不會顯示和執行在網頁上，就算是在程式碼區塊內寫也一樣不會執行。

- 回憶：註解用來說明或備註你的 [[HTML Introduction|HTML]] 程式碼，讓你一陣子後回頭看能理解當初思考邏輯。
- 溝通：其他協同工作者可以知道，為什麼這一個地方的 [[HTML Introduction|HTML]] 會這樣子設計及撰寫。
- 解題：暫時隱藏內容，可暫時將程式做區塊性隱藏或停用，方便以區塊性偵測問題，加快測試跟查找問題。例如：`<!-- <p>content</p> -->`。

## 單行註解 (Single Line Comments)

[[HTML Introduction|HTML]] 註解符號是用 `<!--` 和 `-->` 前後包住你的註解。

```html
<!-- Comment -->
```

```html
<p>This is a paragraph.</p>  
  
<!-- <p>This is another paragraph </p> -->  
  
<p>This is a paragraph too.</p>
```

## 多行註解 (Multi-line Comments)

跟單行註解一樣的，只要是在 `<!--` 和 `-->` 中間的所有內容都會被當成是註解。

```html
<!--
Comment 1
Comment 2
Comment 3
-->
```

```html
<p>This is a paragraph.</p>  
<!--  
<p>Look at this cool image:</p>  
<img border="0" src="pic_trulli.jpg" alt="Trulli">  
-->  
<p>This is a paragraph too.</p>
```

## 行內註解 (Hide Inline Content)

也可在行內註解。

```html
<p>
This
<!-- great text -->
is a paragraph.
</p>
```

```html
<p>This <!-- great text --> is a paragraph.</p>
```