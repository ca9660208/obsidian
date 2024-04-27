---
aliases:
  - 路徑
  - 檔案路徑
---
#unfinished 
# 路徑 (file path)

## 用途

A file path describes the location of a file in a web site's folder structure.

File paths are used when linking to external files, like:

- Web pages
- Images
- Style sheets
- JavaScripts

## 路徑描述

描述文件在網站文件結構中的位置。

- `「」`：是代表目前所在目錄。
- `「.」`：是代表目前所在目錄。
- `「..」`：是代表上層目錄，若目前已經是根目錄則依然為目前所在目錄。
- `「/」`：在各個目錄名稱之間的分隔符號，若放置在路徑之前則代表根目錄。

## 絕對路徑 (absolute path)

絕對路徑指的是這個檔案在本機端或是網路上的絕對位置。

- file://c:/windows/search.html「本機C槽上的一個HTML 檔案」。
- http://www.csie.nuu.edu.tw「網路上一台 WWW Server 上的一個 HTML 檔案」。
- /jang/courses/n12345678「本機 WWW 根目錄下的一個目錄」。

## 相對路徑 (relative path)

相對路徑指的是相對於這個檔案的位置。

- text.html「表同一層目錄下的 text.html 檔案」。
- ./text.html「表同一層目錄下的 text.html 檔案 」。
- image/text.html「表示 image 子目錄下的 text1.gif 檔案 」。
- ../index.html「表示上一層目錄下的 index.html 檔案 」。
- ../html40/cover.html「表示上一層目錄下 html40 子目錄的 index.html 檔案 」。

## Best Practice

It is best practice to use relative file paths (if possible).

When using relative file paths, your web pages will not be bound to your current base URL. All links will work on your own computer (localhost) as well as on your current public domain and your future public domains.

- External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.
- It is almost always best to use relative URLs. They will not break if you change domain.

_At W3Schools we always use lowercase attribute names._