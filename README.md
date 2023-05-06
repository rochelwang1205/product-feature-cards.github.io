# 六角學院2023軟體工程師體驗營 - 切版任務一

This is a solution to the [切版任務作業一 - AI 工具王 - 產品優勢卡片設計](https://rpg.hexschool.com/task/342/show).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [The following goals](#the-following-goals)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview
- 第一次總共花費約1.5小時，0.5小時完成大架構，1小時CSS和HTML調整
- 第二次(包含調整細節)共花費約1.5小時
- 第三次(包含細節設定)花費0.5小時
- 第四次0.5小時含細節，2小時依助教回饋修改

### Screenshot
- 第四次
![](./切版任務一/screenshot.ver.4.png)
- 第二次
![](./切版任務一/screenshot.ver.2.png)
- 第一次
![](./切版任務一/screenshot.png)



### Links

- Solution URL: [product feature cards](https://github.com/rochelwang1205/product-feature-cards.github.io)
- Live Site URL: [product feature cards](https://rochelwang1205.github.io/product-feature-cards.github.io/%E5%88%87%E7%89%88%E4%BB%BB%E5%8B%99%E4%B8%80/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
第一次：
- flex-wrap:wrap
如何將超出畫面外的東西可以根據瀏覽器大小自動換行而不會溢出畫面
- span置右：利用float:right

第二次：
- 照片圓角和邊框圓角存在縫隙，將border-radius改成outline 
- <hr>更改顏色及樣式
- 換成png樣式圖

第三次：
- 寫出emmet的流程
- CSS樣式再微調(像是邊框顏色、寬度)

第四次：
- 卡片用<ul><li>改寫，語意化標籤會優化網頁讀取、取得性(accessibility)
- 標籤層級考慮到整頁的架構，卡片部分改成從h3開始
- 改成<a><span></span></a> ，並改成使用Google Material Icon，方便後續修改大小、字體顏色等
- 加入CSS reset
- .container加上 width: 1296px; justify-content: space-between，更貼合設計稿
- <img>設定 width: 100%;可使圖片自動隨父層元素變動，不必手動調整更簡單方便
- span置右改用flex的方法優化原有較舊且少用的float
- line-height的px改寫成%比例的方式，避免載體不同導致顯示不一致
- <p>段落改用padding推高度
- ctrl+f後，ctrl+shift+L統一修改選取詞
- 字型統一設定在初始設定中。
- 在不限定p段落高度下，如何讓不同行數高度相同?利用em

```css
.container{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    background: white;
    border-radius: 160px;
}
h4{
display: flex;
align-items: center;
justify-content:space-between;
}
.card{
    outline:1px solid rgb(203, 203, 203);/*將border-radius改成outline*/
    margin:15px;
    width:416px;
    border-radius: 16px;
}
hr{  /*更換樣式*/
    border:none;
    height:0.5px;
    background-color:rgb(203, 203, 203);
}
```

### The following goals
第一次：
- icon要改用已經有給的圖，不然大小跟設計稿會不一樣
- 螢幕顯示器調整
- Emmet 寫架構要再調整練習
- 細節（間距）要再根據設計稿細調（因為有些為目測結果）
第二次：
- 練速度跟emmet!
第四次：
- <hr>改用CSS中的border

### Useful resources

- [flex-wrap](https://developer.mozilla.org/zh-CN/docs/Web/CSS/flex-wrap)
- [ionicons](https://ionic.io/ionicons/)
- [The 3 CSS Methods for Adding Element Borders](https://moderncss.dev/the-3-css-methods-for-adding-element-borders/)
- [Day16 CSS排版之神flex](https://ithelp.ithome.com.tw/m/articles/10275225)
- [實際展示 EM 與 REM 的差異](https://www.hexschool.com/2016/01/02/2016-08-08-em-vs-rem/)

## Author

- Website - [Rochel Wang](https://github.com/rochelwang1205)
- Frontend Mentor - [@Rochel Wang](https://www.frontendmentor.io/profile/rochelwang1205)
- Twitter - [@RochelWang4](https://twitter.com/RochelWang4)

