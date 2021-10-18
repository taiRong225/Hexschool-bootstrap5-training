# Hexschool-bootstrap5-training
## About Project
六角學院 21 天帶您做出 Bootstrap 5 募資網站

舉辦單位：[六角學院 Hexschool](https://www.hexschool.com/ "六角學院 Hexschool")

活動時間：2021/05/11 ～ 2021/06/08

## Project Link 作品連結
- [作品展示](https://tairong225.github.io/Hexschool-bootstrap5-training/index.html "作品展示")

## 學習重點
1. 紀錄必要資訊
2. 劃分元件區域
3. 客製化變數、通用類別、元件

### 紀錄必要資訊
1. 圖示 icon
2. 色系 theme-color
3. 字型 font-family
4. 字體等級 font-size
5. 文字行高 line-hight
6. 文字間距 letter-sapcing

### 元件
1. 導航列 Navbar
2. 商品 Product
3. 頁籤 Tab
4. 下方內容主要區域
    - 頁籤內容區域 Tab-content
        - 專案介紹 Project
        - 常見問答 Faq
        - 目前進度 Progress
        - 留言 Message
    - 贊助專案 Form
    - 店家資訊 Store
    - 方案列表 Plan
5. 頁尾 Footer
6. 登入Modal

### 客製化變數、通用類別、元件
``` scss
// Configuration
@import '../node_modules/bootstrap/scss/functions';
@import 'custom/variables'; // 自定義變數
@import '../node_modules/bootstrap/scss/variables';
@import '../node_modules/bootstrap/scss/mixins';
@import '../node_modules/bootstrap/scss/utilities';

// Utilities
@import 'custom/utilities'; // 自定義通用類別

// Bootstrap
@import '../node_modules/bootstrap/scss/bootstrap';

// Component
@import 'custom/nav';
@import 'custom/accordion';
@import 'custom/footer';
@import 'custom/button';

// Google-Fonts
@import '_google-fonts.scss';
