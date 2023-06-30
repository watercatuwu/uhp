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

### 圖床

圖片可以直接放在文章資料夾中，不過**非常不建議**

會造成存儲庫檔案肥大，以及路徑遺失等問題

可以使用imgur之類的圖床網站作為圖床

我自己是使用github作為圖床

~~discord也是一個非常讚的圖床~~

只要上傳複製連結即可

### 上傳存儲庫(合併分支)

編輯完存到自己的存儲庫後

發出pull request向兔百的存儲庫提交分支

![](https://raw.githubusercontent.com/watercatuwu/uhp/pic/20230630160309.png)

加上標題、詳細資訊(可選)，並送出

![](https://raw.githubusercontent.com/watercatuwu/uhp/pic/20230630160448.png)

等待兔百存儲庫同意就OK了，接下來的動作都會由伺服器端自動處理

### 同步存儲庫

![](https://raw.githubusercontent.com/watercatuwu/uhp/pic/20230630153307.png)

當這邊出現有新的分支提示時，請記得**一定**要同步兔百的存儲庫(Sync Fork)

不然會造成別人辛苦寫的文章消失

### 流程圖(給也想要自己做一個這樣的系統的人)

![](https://raw.githubusercontent.com/watercatuwu/uhp/pic/%E6%9C%AA%E5%91%BD%E5%90%8D.png)

~~小畫家 讚~~
