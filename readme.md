這次的期末專題簡介：運用html CSS 做出網頁外觀和型態設計 再用javascript寫出亂數抽籤的程式以及運作的時間前後、延遲等
使用者要怎麼使用你的網站：
使用這個網站很簡單，只要閱讀網站最上方的提示便可使用，簡單而言就是點一下下方紅色的按鈕，我特別做成gif檔，
之後點下去會出現抽籤的動畫，並且出現籤文及第幾支籤，記住籤文的內容後，按下右上角的X便可以關掉，這時候會跳出一個視窗讓你可以連結到
解釋籤文的網站，也就是籤文來源的網站，作查詢，或者是回到上一頁，再做一次抽籤
你在這次專題中做了什麼，使用了什麼技術：
這次專題除了用html,CSS做出網頁設計，觸碰按鈕會上移等互動之外，最重要的就是使用javascript做出類似動畫的效果，因為我想在按下按鈕
，也就是onclick,function後跑出抽籤的動畫，接著才出現籤文內容，所以還特別使用setTimeout的功能，讓gif跑完的那一刻出現，但因為javascript
的亂數是一開始就決定的，所以抽完籤後，會跳出一個視窗讓他們選擇去看籤文內容，或返回上一頁重新求籤，因為是重新整理所以，亂數也會重新刷新
使得抽出來的籤會不同。
在設計的時候，左右兩側的紅色是因為廟裡的籤通常都是紅色，且在跳出視窗的時候也會剛好遮住左右兩側的空白，不會使其太突兀，
因為籤文的部分我使用position:fixed;而亂數是用javascript 的Math.random 中用字串代替遠本只能隨機跳出數字，而能隨機出現圖片，
而setTimeout的部分則是花了我很多時間研究，因為有很多方法又不是講得很清楚，甚至還有網路上的程式碼有缺漏無法使用，卡了大半天。