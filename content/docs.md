---
title: "教學"
description: "兔百文檔"
---

# 新增、編輯

> 更新於2023.9.20

## Required

- Github帳號
- 跟溺水貓取得存儲庫使用權
> (請洽Discord:@watercatuwu、Gmail:watercat0330@gmail.com)(Discord比較常看)

## 編輯器選擇

一般做小修正直接用github網頁編輯器就行

新增條目涉及到複製資料夾，用vscode比較方便

github有提供線上版的vscode--**github.dev**

直接把網址列.com改成.dev

`github.com -> github.dev`


## Markdown??

hugo使用的語法為markdown語法

跟Discord聊天的文字效果邏輯類似

詳細可以到[這篇文章](https://hackmd.io/@mrcoding/H1_y9aB5N)

或是[說明文件](https://markdown.tw/)

另外也支援HTML/CSS，會用的話能做出更多文字、圖片效果

即時預覽的部分Github編輯器就有Preview功能了

![](https://cdn.discordapp.com/attachments/1046603288251990099/1153973258434138142/image.png)

Github.dev也能安裝Markdown預覽插件(自行Google**"vscode 插件"**)

## 新增條目

> 請使用github.dev 線上版vscode

[空白模板參考](https://github.com/watercatuwu/uhp/tree/template)

文章都位於`/content/posts`

結構為

```
/content/posts
|_兔姬
    |_featured.png(縮圖、可選)
    |_index.md(文章檔)
```

![](https://cdn.discordapp.com/attachments/1046603288251990099/1154280280014716989/image.png)

### 新增條目步驟

1.新增資料夾，資料夾名為文章名稱

2.新增文件`index.md`

資料夾內`featured.png`做為背景圖片以及預覽圖，留空則為預設背景

```
---
title: "文章範例"   <-- 網頁標題
date: 2023-06-29    <-- 編輯日期
draft: false    <-- 這不用動
description: "範例，這是個範例" <-- 網頁詳細介紹
slug: "範例"    <-- 文章名稱(顯示於網址 請設定為一樣的)(https://usagi.xeift.tw/範例)
tags: ["uwu","awa"] <-- 分類標籤(tag)
---

# 文章寫在此處

```

## 編輯條目

每個文章開頭都有個小小的編輯按鈕

有取得存儲庫權限的話就能直接編輯了

![](https://cdn.discordapp.com/attachments/1046603288251990099/1153972288752975892/image.png)

## 寫完了，然後呢?

記得Push儲存 接下來就會自動更新到網站上(約1~2min)

![](https://cdn.discordapp.com/attachments/1046603288251990099/1154282185726120056/image.png)

## 補充說明:圖床

圖片雖能直接上傳在文章資料夾中，不過**非常不建議**

會造成存儲庫檔案肥大，以及路徑遺失等問題

所謂圖床，就是一個放圖片的網路空間

discord也能作為圖床

只要上傳後複製連結即可


# 流程圖(給也想要自己做一個這樣的系統的人)

![](https://raw.githubusercontent.com/watercatuwu/uhp/pic/%E6%9C%AA%E5%91%BD%E5%90%8D.png)

~~小畫家 讚~~
