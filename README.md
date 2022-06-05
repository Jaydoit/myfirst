問答題
1. Bootstrap 4 中提供何種方式讓使用者進行頁面上的設計?
 ANS:HTML、CSS 和 JavaScript 
2. Bootstrap 4 中 container、container-fluid 差異為何?
 ANS:container和container-fluid差別:container有margin,container-fluid沒有margin。
                                   container當螢幕到特定大小時，才會改變,container-fluid會跟隨著螢幕大小來改變。
3. Bootstrap 4 中切版最多可分成幾等份?
 ANS:12等分
#4
1.使用迴圈的方式列印 99 乘法表
              <?php
              for ($i=2, $j=1; $i < 9 || $j <= 9 ; $j++)
              {
                 if ($j > 9)
               {
                $i++;
                $j = 1;
                echo "<br>";
               }
                echo "$i*$j=" . $i * $j . ", ";
              }
3.以下題目請使用 Javascript 或者 JQuery 語法完成
  1. 用 HTML 寫出簡易表單,表單的按鈕點擊之後在頁面顯示表單內容。
ANS:
<form action="signup" method="post">
帳號: <input type="text" name="user"/><br/>
密碼: <input type="password" name="password"/><br/>


<input type="submit" value="送出"/><input type="reset" value="清除"/><br/>
</form>
