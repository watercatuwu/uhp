---
title: "教學"
description: "兔百文檔"
---

## 新增、編輯條目教學

### Required

- Github帳號


### 取得百科檔案

登入github帳號後，打開[兔百的存儲庫](https://github.com/watercatuwu/uhp)


Fork兔百存儲庫

![](https://raw.githubusercontent.com/watercatuwu/uhp/pic/20230630111956.png)

創建自己的存儲庫

![](https://raw.githubusercontent.com/watercatuwu/uhp/pic/20230630112116.png)

### Markdown??

hugo使用的語法為markdown語法

詳細可以到[這篇文章](https://hackmd.io/@mrcoding/H1_y9aB5N)

或是[說明文件](https://markdown.tw/)

另外也支援HTML，可以使用HTML語法做出更多文字、圖片效果

需要即時預覽可以於[stackedit](https://stackedit.io/)等網站進行編輯

### 新增條目

存儲庫中文章的存放位置於`/content/posts`

裡面有個文章範例資料夾，直接複製即可

改好資料夾名稱後，於`index.md`中編輯

```
---
title: "文章範例"   <-- 網頁標題
date: 2023-06-29    <-- 編輯日期
draft: false    <-- 草稿? 預設不開我就沒動
description: "範例" <-- 網頁詳細介紹
slug: "範例"    <-- 網址顯示 (https://uwu.com/範例)
tags: ["uwu","awa"] <-- 分類標籤
---

【文章寫在這邊】

```

### 圖床

我自己是使用github作為圖床

懶得話也可以直接丟到discord複製連結

### 上傳伺服器

(待補...)