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
總共花費約1.5小時，0.5小時完成大架構，1小時CSS和HTML調整。

### Screenshot

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

-flex-wrap:wrap
如何將超出畫面外的東西可以根據瀏覽器大小自動換行而不會溢出畫面。
-span置右：利用float:right

```css
.container{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    background: white;
    border-radius: 160px;
}
span{
    float: right;
}
```
### The following goals
-icon要改用已經有給的圖，不然大小跟設計稿會不一樣
-螢幕顯示器調整
-Emmet 寫架構要再調整練習
-細節（間距）要再根據設計稿細調（因為有些為目測結果）
### Useful resources

- [flex-wrap](https://developer.mozilla.org/zh-CN/docs/Web/CSS/flex-wrap)
- [ionicons](https://ionic.io/ionicons/)

## Author

- Website - [Rochel Wang](https://github.com/rochelwang1205)
- Frontend Mentor - [@Rochel Wang](https://www.frontendmentor.io/profile/rochelwang1205)
- Twitter - [@RochelWang4](https://twitter.com/RochelWang4)

