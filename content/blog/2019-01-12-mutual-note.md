---
title: 使用 Hackmd 製作系上共筆的可行性？
date: 2018-08-11
updated: 2018-08-11
taxonomies:
  categories: 
    - 醫學
  tags: 
    - medicine
    - study
---

前幾天排版共筆排得很煩躁，腦中突然冒出用 Hackmd 製作系上共筆的想法。網上搜尋了一下，發現沒有人寫類似的文章（大概也沒有人會公布自己系上製作共筆的方式吧，除了以前[黃豆泥](https://youtu.be/Ur_uvrLKtQ4)學長有推廣過使用 Google Docs 製作共筆）。所以趁著整合考剛結束，理了一下想法，順手打下。

<!-- more -->

## 什麼是共筆？
共筆，共同筆記，由一群人共同製作的筆記。據我所知，其實不只有醫學系有這個制度，法律系以及一些會議、演講也都會製作共筆，方便同學和與會者共享知識內容 (像是使用下面提到的 Hackmd)。

目前我們系上製作共筆的流程如下：組員 → 組長 → 組頭 → 學藝 。
老師上完課後，由五到六個組員將投影片內容製作成共筆，接著組長排版、組頭審核內容，最後交給學藝進行最終把關並送印。

## 什麼是 Hackmd？
其實有點類似 Google Docs，同樣提供線上協作的文字編輯服務，但最大的不同點在於 Hackmd 使用了 Markdown 語法進行文件的撰寫。

那什麼是 Markdown？

> Markdown 是一種輕量級標記式語言，它允許人們「使用易讀易寫的純文字格式編寫文件，然後轉換成有效的 XHTML（或者 HTML）文件」。

這是[維基百科](https://zh.wikipedia.org/wiki/Markdown)上對於 Markdown 的介紹，重點就在於「易讀易寫」這四個字。我們可以使用一些簡單的符號輕鬆建立一篇排版工整且易於閱讀的文件，手甚至不需要離開鍵盤。比起 Word 必須使用滑鼠點來點去進行版面的調整，Markdown 可說是節省許多時間與麻煩。有興趣的人可以參考[這篇](https://markdown.tw/)詳細的 Markdown 語法教學。

> 補充：其實 Markdown 有很多種版本，例如 [John Gruber 發明的原始版本](https://daringfireball.net/projects/markdown/)和 [Github-flavored Markdown (GFM)](https://help.github.com/categories/writing-on-github/) 等，不過最基本的功能都是一樣的。而 Hackmd 在最基本的 Markdown 功能之外，也有許多獨創的語法。

## 使用 Hackmd 製作共筆的好處？
Word 是現今最為普遍使用的文書處理軟體，也是大多數人打文件的首選，系上的共筆製作當然也不例外。因為它太強大了，能夠使用很多複雜的功能，所以目前看來似乎沒有理由轉換成 Hackmd (Markdown)。

說來很不可置信，其實還是有很多同學對於 Word 的功能不太熟悉，例如不會設定編號、不會調整圖文的版面配置等，也導致組長需要花費很多時間調整排版。雖然現在大多數的共筆都是修改自學長姐的檔案，版面不太需要調整，因此問題不大。但有時候老師一換，必須從零開始製作時，排版工作真的是一大災難。假如我們使用 Hackmd，整個製作流程也許可以更輕鬆寫意。

~~（不過老實說，一個連 Word 都不肯好好學的人，怎麼會願意認識這一輩子可能都用不到的 Markdown 呢～）~~

## Demo
![demo](https://drive.google.com/uc?export=view&id=1pfy2zV6IjetJ2bNtrjkMz037hcGxlZy0)

在這種條列式的使用情境下，Hackmd 能做得跟 Word 不相上下，而右側文字實際上使用 Markdown 語法是長下面這樣：
```
### B. 定義與發生率(Definition and Incidence)
#### 一、定義、診斷
1. 急性胰臟炎是指一種胰臟急性發炎並且涉及其他區域的組織或遠處的器官系統的一個過程（1992 Atlanta Symposium）。
2. 以下3點符合2點即可診斷為急性胰臟炎
    * 典型的持續性的腹痛（++上或左上腹痛++、痛連背部、身體蜷曲會減緩痛感）
    * 血清中澱粉酶(amylase)、脂肪酶(lipase)的數值高於正常值三倍以上
    * 在腹部影像學檢查中有屬於典型急性胰臟炎表現（比如說胰臟腫大、偽囊腫等等的）

#### 二、發生率
1. 急性胰臟炎在全球的發生率大概為 4.9\~73.4/100,000。西方盛行率約10~20 %左右，台灣偏低大概只有5 ~10 %。
2. **膽結石(gallstone)** 是世界上急性胰臟炎最常見的病因。西方國家甚至超過1/2的AP患者是因為膽結石！
3. 性別比方面：
    * 膽結石所造成的急性胰臟炎→女性患者>男性患者
    * 喝酒所造成的急性胰臟炎→男性患者>女性患者

### C. 危險因子(Predisposing Conditions)
1. 在美國，75 %的AP患者與膽結石、酗酒這兩個因素有關；另外≤ 30 %的患者無明顯病因，稱為自發性胰臟炎(idiopathic pancreatitis)。
2. 在台灣，膽結石性胰臟炎佔41.9 %，酒精性佔14.9 %，原因不明佔27 %。
3. 下圖為常見的阻塞位置，大部分是在膽囊裡面，其實大多的結石都是無症狀(silence)，所以不一定會發現，但是當結石卡在遠端總膽管(CBD)附近時，會一起堵住胰管造成胰臟發炎，也有可能造成黃疸問題，因此看到黃疸得要考慮是肝臟還是膽管問題，而病人的主訴是痛的話就可能要優先考慮是膽道問題。

![](https://i.imgur.com/R6xOaxQ.png)
```

可以看出 Markdown 是藉由各種符號來達到粗體、斜體、標號等效果，省了排版美化的時間。

## 待克服的問題
### 1. 共同編輯
Hackmd 有很多種筆記[權限](https://hackmd.io/s/E1UakUq8#權限)設置，要怎麼給予同學適合的權限是個滿重要的問題。

> 可能的解決方法：全程使用「Editable」。

### 2. 表格
共筆中常常會使用表格來統整概念，偏偏我覺得 Markdown 的表格不太好用，功能太陽春了，像是合併儲存格等較進階的方式在 Markdown 就沒辦法使用。

> 可能的解決方法：若要製作比較複雜的表格，可能要先在其他軟體中製作後再截圖貼到 Hackmd。(但這樣實在不太方便 )

### 3. 圖片
一般我們在 Word 中對於圖片的操作不外乎調整「大小」和「排列方式」。Markdown 中調整圖片大小容易，但對於排列方式的支援就不是那麼好，沒辦法文繞圖、置中等。

> 可能的解決方法：無解。一開始我以為這會是個大問題，但後來發覺其實看習慣就還好。

### 4. 輸出
Hackmd 目前不支援 PDF 格式的輸出，對於印出紙本或是在平板上閱讀都不太方便。

> 可能的解決方法：最簡易的方法就是使用瀏覽器(如 Chrome)輸出，只可惜有的格式會跑掉。

## 總結
儘管有一些問題需要克服，但整體而言，Hackmd 仍不失為一個製作共筆的好工具。現在大家都用學長姐的檔案輕鬆交差，大概也不可能改變製作過程，這篇文章只是在發牢騷罷了XD