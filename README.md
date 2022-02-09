# wordle_solve
<br>
總之呢就是一個很土炮的幫你猜辣
<br>
使用網址如以下
<br>
https://sleepyknife.github.io/wordle_solve/

<hr>

<p>這是一個給懶人使用，幫忙猜wordle 遊戲的懶人網站</p>
<p>這個網站只能幫你猜今天的單字，沒有報明牌的功能</p>
<h1>使用方法：</h1>
<hr>
<p>1. 第一行輸入你猜的文字</p>
<p>2. 第二行依照以下規則輸入wordle 的結果</p>
<table style="border:3px #cccccc solid;" cellpadding="10" border='1'>
  <tr>
    <td>符號</td>
    <td>意思</td>
  </tr>
  <tr>
    <td>+</td>
    <td>綠色：有此文字且位於<b>正確位置</b>！</td>
  </tr>
  <tr>
    <td>?</td>
    <td>黃色：有此文字但位於<b>錯誤</b>位置！</td>
  </tr>
  <tr>
    <td>*</td>
    <td>灰色：<b>無此文字</b></td>
  </tr>
</table>
<hr>

**演算法主要依照以下三個步驟：**
<br>
**+:絕對位置mapping**
<br>
**-:保留交集文字**
<br>
**\*: 排除交集文字**
<br>
目前沒把常用字機率加進去，總之就只是幫你猜而已
<br>
88
