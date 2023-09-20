---
title: "教學"
description: "兔百文檔"
---

## 新增、編輯

> 更新於2023.9.20

### Required

- Github帳號
- 跟溺水貓取得存儲庫使用權
> (請洽Discord:@watercatuwu、Gmail:watercat0330@gmail.com)(Discord比較常看)


### Markdown??

hugo使用的語法為markdown語法

跟Discord聊天的文字效果邏輯類似

詳細可以到[這篇文章](https://hackmd.io/@mrcoding/H1_y9aB5N)

或是[說明文件](https://markdown.tw/)

另外也支援HTML/CSS，會用的話能做出更多文字、圖片效果

即時預覽的部分Github編輯器就有Preview功能了

![](https://cdn.discordapp.com/attachments/1046603288251990099/1153973258434138142/image.png)

### 新增條目

[空白模板參考](https://github.com/watercatuwu/uhp/tree/template)

文章都位於`/content/posts` 

新增文章直接新增文件，名稱格式為`文章名稱/index.md`

例如:`兔姬/index.md`

資料夾內`featured.png`做為背景圖片以及預覽圖，留空則為預設背景

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

### 編輯條目

每個文章開頭都有個小小的編輯按鈕

有取得存儲庫權限的話就能直接編輯了

![](https://cdn.discordapp.com/attachments/1046603288251990099/1153972288752975892/image.png)

### 補充說明:圖床

圖片雖能直接上傳在文章資料夾中，不過**非常不建議**

會造成存儲庫檔案肥大，以及路徑遺失等問題

所謂圖床，就是一個放圖片的網路空間

discord也能作為圖床

只要上傳後複製連結即可


### 流程圖(給也想要自己做一個這樣的系統的人)

![](https://raw.githubusercontent.com/watercatuwu/uhp/pic/%E6%9C%AA%E5%91%BD%E5%90%8D.png)

~~小畫家 讚~~
