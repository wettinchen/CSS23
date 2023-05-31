## CSS Chapter 23
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 CSS 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6Mx9fd9elt80G1bPcySmWit

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## CSS Chapter 23
   Quick Concept outline
   中文摘要說明與重點提問

###  1. Intro
        教學影片固定的開頭

###  2. Welcome
        歡迎觀眾，說明工具與資料位置

###  3. Follow Your Team
        First Suggenstion to Organize your CSS

###  4. Create Headings with Comments
        Second Suggenstion to Organize your CSS

###  5. Sort CSS properties by ABCSS or groups
        Third Suggenstion to Organize your CSS
        Ctrl + P 輸入 > ，使用 Sort Line Ascending 指令排列 body 的 屬性

###  6. Naming Convention Methodologies
        Forth Suggenstion to Organize your CSS

###  7. BEM - Blocks
        First part of Naming Convention Methodologies

###  8. BEM Blocks with Modifiers
        Second part of Naming Convention Methodologies

###  9. BEM Blocks vs Elements
        Third part of Naming Convention Methodologies

### 10. Header example styles
        (1)新增 .header 的背景為 var(--HEADER-BGCOLOR)，文字顏色為 var(-COLOR)，padding 為 1rem 1rem 0.5rem，display 為 flex，flex-flow 為 row nowrap，justify-content 為 space-between
        (2)移除 body 的 justify-content, align-items, gap
        
### 11. BEM Elements
        修改 .btn 為 .header__btn

### 12. BEM Elements with Modifiers
        (1)修改 .btn--secondary 為 .header__btn--secondary
        .btn--lean 為 .header__btn--lean
        .btn--border-lg 為 .header__btn--border-lg
        (2)設定第三個按鈕背景為黃色

### 13. BEM helps keep specificity aligned
        BEM Selector Specificity: (0, 1, 0)
        .header button 的 Selector Specificity: (0, 2, 1)