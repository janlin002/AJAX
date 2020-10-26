# AJAX
AJAX的課程筆記

<h3>readyState狀態碼：<br></h3>
0-已經已經產生一個xmlhttprequest，但還沒連接要撈的資料<br>
1-用了open()，但還沒把資料，但還沒把資料傳送過去<br>
2-偵測到你有用send()<br>
3-loading資料太大<br>
4-成功<br>

<h3>同步與非同步</h3><br>
true 非同步：不等資料傳回來，就先往下跑<br>
false 同步：等到資料回傳，才往下跑<br>


<h3>onload:<br></h3>
如果上方資料有回傳，就執行<br>


<h3>status(http狀態碼):<br></h3>
200-資料有正確回傳，有撈到<br>
404-資料讀取錯誤，沒有撈到<br>


<h3>CORS<br></h3> 
是否可以跨網域，撈取資料<br>
推薦資源：https://www.test-cors.org/
