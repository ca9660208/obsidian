# 基本觀念

## 組成

由最小單位的[[Element|元素]]以[[Nesting|巢狀]]寫成。

```html
<!DOCTYPE html>
<html>
	<head>
		<title>Page Title</title>
	</head>  
	<body>
		<h1>My First Heading</h1>
		<p>My first paragraph.</p>
	</body>
</html>
```

每一個 [[HTML Introduction|HTML]] [[Tag|標籤]]包圍的[[Content|內容]]，可以再包含其他的 [[HTML Introduction|HTML]] [[Tag|標籤]]，所以說 [[HTML Introduction|HTML]] 文件的結構是屬於一種階層的樹狀 ([[Nesting|巢狀]]) 結構。

在樹狀結構裡，處於外層的元素稱作「父元素 (parent element)」，內層元素稱為「子元素 (child element)」，父元素和子元素是一種相對關係。

```
                 ┌───────┐
                 │ html  │
                 └───┬───┘
                     │
    ┌────────────────┴────────────────┐
    │                                 │
┌───┴───┐                         ┌───┴───┐
│ head  │                         │ body  │
└───┬───┘                         └───┬───┘
    │                                 │    
┌───┴───┐                    ┌────────┴────────┐
│ title │                    │                 │
└───────┘                ┌───┴───┐         ┌───┴───┐
                         │  h1   │         │   p   │
                         └───┬───┘         └───┬───┘
                             │                 │
                            text              text
```

![[Pasted image 20240411021228.png]]

## HTML 文件基礎

依造基本規則創建檔案後，只要依照需求來使用[[Tag|標籤]]，並且給予[[Attribute|屬性]]跟[[Content|內容]]來建立網頁結構即可。

### HTML 基本架構

| 元素                | 說明                                                             |
| ----------------- | -------------------------------------------------------------- |
| `<!DOCTYPE html>` | 定義 [[HTML Introduction\|HTML]] 的類型 (doctype)，只要是網頁都會需要放入這段程式碼。 |
| `<html></html>`   | 「根元素 (root element)」，包含了所有顯示在這個頁面上的內容。                         |
| `<head></head>`   | head 元素，網頁不會被使用者看到，但卻是必須具備的重要資訊。例如：網頁標題、頁面說明、CSS...等。          |
| `<body></body>`   | body 元素，所有要讓使用者看到的內容。                                          |

### HTML 基礎規範

- 必須以`<!DOCTYPE html>`文檔類型開頭。
- 必須要有 `<html>`、`<head>`、`<body>`。
- [[HTML Introduction|HTML]] 的內容置於`<html>`開頭`</html>`結尾之間。
- [[HTML Introduction|HTML]] 的「元資訊 / 元資料 / 後設資料 (metadata / mata info / mata infomations)」 置於`<head>`開頭`</head>`結尾之間。
- [[HTML Introduction|HTML]] 可見[[Content|內容]]置於`<body>`開頭`</body>`結尾之間。
- 文件內容由[[Element|元素]]以[[Nesting|巢狀]]的方式寫成。

```html
<!-- 聲明這是一份採用 HTML5 語法標準的文件。 -->
<!DOCTYPE html>
<!-- 文件的根元素 -->
<html>
	<!-- 不會被顯示在頁面上的內容，用來說明關於該網頁的元資訊-->
	<head>
		<title>Page Title</title>
	</head>
	<!-- 會被顯示在頁面上的內容 -->
	<body>
		<h1 class="title">My First Heading</h1>
		<p>My first paragraph.</p>
	</body>
</html>
```

## Hello World

1. 創建新文件。
2. 撰寫 [[HTML Introduction|HTML]]。
3. 儲存文件。
4. 副檔名存為 .html 或 .htm。
5. 編碼存為 UTF-8。_最適合 HTML 的編碼。_
6. 使用[[Browser|瀏覽器]]開啟檔案即可看到結果。
  
_副檔名存為 **.htm** 或 **.html** 兩者無差別。最常用也建議的副檔名為.html。_

```html
<!DOCTYPE html>
<html>
	<head>
		<!-- Write metadata here -->
		<title>Page Title</title>
	</head>
	<body>
		<!-- Write document here -->
		<h1>My First Heading</h1>
		<p>My first paragraph.</p>
	</body>
</html>
```

## Suggest

### 檔案名稱使用小寫字母

雖然在 [[HTML Introduction|HTML]] 存檔時可以用大小寫命名。例如：Apple.html 和 apple.html。

但不同的[[Browser|瀏覽器]]會有不同的讀取規則，有些[[Browser|瀏覽器]]會區分檔名的大小寫，有些則會認為是同一個檔案，因此建議檔案名稱一律使用小寫字母，並且避免特殊字元或中文字。_因爲這些文字也會被轉換成字母和數字。_