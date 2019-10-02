# 107 學年度應用統計學專題

## 研究主題：Youtube觀看次數大解析
指導老師：李信宏 教授

組員： 
* S0522108 洪羽柔
* _**<font color="#660000">S0522112 艾品璇</font>**_
* S0522131 陳晏琦
* S0522143 顏均翰

## 研究動機

身處在資訊流通快速、人手一台智慧型手機的時代下，隨著各年齡層使用社群媒體的時間大幅提升，許多的應用程式紛紛被廣為轉載、使用，而Youtube成為了使用較頻繁的平台之一。
    
由於Youtube這個平台相較於電視節目，可以免費自己開立一個專屬的頻道，因此各種類型的影片開始被拍攝放在平台上給大家觀賞，不論是教育型、生活型、寵物型…等影片，都迅速累積了許多忠實觀眾，透過觀看Youtube影片能夠打發時間、放鬆心情之外，還能利用Youtube來吸收各方面的知識。甚至許多的新聞、電視節目，除了在電視上播放外，也會使用Youtube這個平台來讓更多的族群能夠觀賞到。逐漸的，政治、經濟開始與Youtube產生連結，進而發現Youtuber這個「職業」，可以藉由拍攝影片來累積觀看次數，且觀看次數的多寡也與Youtuber的收入有所關聯。
    
除此之外，也能帶來額外的效益，像是廣告的置入、品牌代言、知名度的提升，都會是在拍攝影片之餘能夠獲得的利益，因此想探討什麼原因會影響到觀看次數，藉此知道，相對應的收入該是如何？因此，上述的原因是引起了想要研究Youtube的動機。藉此利用課堂上所學習到的迴歸分析技術，來深入探討影響Youtube影片觀看次數的原因。

## 研究方法

1.決定要關注的特徵值、變數

2.透過下列分析方式挑選出統計模型        
* Stepwise Selection
* Forward Selection
* Backward Elimination
* Best Subsets Regression        

3.透過迴歸分析找出最終的統計模型
* 初步檢視迴歸分析
* 離群值(outlier)分析
* 檢查迴歸假設

## 結論

從迴歸分析結果，可以得知 Youtuber的頻道訂閱數(X1) 、 Youtuber的臉書追蹤人數(X2)以及頻道類型(人物與日誌X11)，的確顯著影響觀看次數Y，從R-sq(adj)= 46％來看，此三個自變數大約可以解釋約46％ Youtube影片觀看次數(Y)的變化量。

因此，想要有較高的觀看次數，就需設法提高頻道訂閱數和臉書追蹤人數，而且拍攝內容是屬於人物與日誌類型的影片。

不過由於選取的Youtuber並非為剛起步之Youtuber，也就是資料中的各個Youtuber皆是擁有至少40萬的訂閱數，因此該模型並不適合套用於剛創立的頻道。

可惜的是此迴歸模型只能解釋不到一半的影片觀看次數，代表還有其他尚未探討到的因素會影響影片的觀看次數，期許在未來能夠發現其他因素，也希望將來的資料能夠擴展至全球Youtuber以發展出新的模型。
