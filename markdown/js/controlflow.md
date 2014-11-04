程式執行
--------

從上往下，一行一行跑

控制只有「部分」會執行：`if` 條件式

控制「某部分重複執行」：`for` 迴圈

---

`if` 條件
--------

`if` - `else if` - `else`

[[mrorz-js-if?javascript,console]]

---

LearnStreet 練習時間
--------

「Control Structures」的[練習連結](http://www.codecademy.com/courses/javascript-beginner-en-8j9pu/1/5#!/exercises/0)

![If](images/js/code-if.png)

約需 16 分鐘。

---

<div class="row">
  <div class="span3">
    <h4>1. Max of Two</h4>
    <p><small>回傳 `a`, `b` 中較大者。</small></p>
    <h4>2. Best of Three</h4>
    <p><small>回傳 `a`~`c` 中最大者。</small></p>
    <h4>3. Doesn't JS Rock?</h4>
    <p><small>依照 password 是否正確，回傳對應訊息。</small></p>
    <h4>4. Are you Chuck Norris</h4>
    <p><small>只在 `username` 與 `password` 為指定值時才回傳 `successMessage`。</small></p>
  </div>
  <div class="span3">
    <h4>5. Find the Number</h4>
    <p><small>當 `a`、`b`、`a+b`、`a-b`、`b-a` 任一為 `42` 時回傳 `true`</small></p>
    <h4>6. Five Letter Palindrom</h4>
    <p><small>回傳是否為五字迴文。</small></p>
    <p><small>註：若非五字，請記得回傳 `false`。</small></p>
    <h4>7. FizzBuzz</h4>
    <p><small>檢查 `num` 是否為 3 及 5 的倍數，回傳相對的文字。</small></p>
    <h4>8. Nested If-Else Statements</h4>
    <p><small>給定星期幾和天氣，決定應該要做什麼。</small></p>
  </div>
</div>

---

`while` 迴圈
-----------

```js
while(true){
  …重複執行的程式碼…
}
```
------
把下面程式貼進 Javascript 控制台

```js
while(true){
  console.log("一直一直執行呀～");
}
```

---

You need a `break`
-----------

從 0 印到 9 的範例。

[[efoGerO?javascript,console]]

`break` 敘述可以跳出迴圈。

---

範例：手機號碼
-----------

[[mrorz-js-numcheck?javascript,console]]

<p class="fragment">來實作 `numCheck` 吧！</p>

---

逐字檢查 (1)
-------

先檢查「整個字串僅含阿拉伯數字與 "-"」。

[[mrorz-js-numcheck?javascript,console]]

註：Javascript 字串可以用 `<`、`>`，比字典順序。

---

逐字檢查 (2)
------

加入判斷「數字要有 10 個」

[[OROFefe?javascript,console]]

---

成品
-----

[[AJETOfa?javascript,console]]

---

繼續執行條件
-----------

```js
while(繼續執行條件){
  …重複執行的程式碼…
}
```

[[iSIHoBa?javascript,console]]


---

`for` 迴圈與 `while` 迴圈
--------------------

<div class="row">
  <div class="span3">
    <pre><code class="javascript">while(繼續條件){
  …重複執行的程式碼…
}</code></pre>

  </div>
  <div class="span3">
    <pre><code class="javascript">for(;繼續條件;){
  …重複執行的程式碼…
}</code></pre>

  </div>
</div>

從 0 印到 9 的範例。

[[InoCOmI?javascript,console]]

---

`for` 迴圈細節
--------------------

<div class="row">
  <div class="span3">
    <pre><code class="javascript">初始化;
for(;;){
  …重複執行的程式碼…
}</code></pre>

  </div>
  <div class="span3">
    <pre><code class="javascript">for(初始化; 繼續條件; 條件改變){
  …重複執行的程式碼…
}</code></pre>

  </div>
</div>

[[otEceku?javascript,console]]

<p class="fragment">
`for` 迴圈 `( )` 完整描述了迴圈的運作，<br>`{ }` 裡頭只要放真正的執行邏輯。
</p>

---

LearnStreet 練習時間
--------

「Loops」的[練習時間](http://www.codecademy.com/courses/javascript-beginner-en-8j9pu/2/1)

![Learn loop](images/js/code-loop.png)

約需 20 分鐘。

若按 Run 沒有回應，請重新整理。

---

<div class="row">
  <div class="span3">
    <h4>1. Add 'Em Up</h4>
    <p><small>用 `for` 算從 `1` 加到 `n`。</small></p>
    <h4>2. Sum Odd Numbers</h4>
    <p><small>同 1，但只加奇數。</small></p>
    <h4>3. Count how many "a"</h4>
    <p><small>計算一串字裡頭有多少 `a`。</small></p>
    <h4>4. How many percent of one basic group in a DNA</h4>
    <p><small>計算 `A`、`T`、`C`、`G` 在有一串DNA佔有多少比率。</small></p>
  </div>
  <div class="span3">
    <h4>5. How two are DNA are similar</h4>
    <p><small>用 `for` 比較兩個一樣長的 DNA 有多少相似度</small></p>
    <h4>6. Palindrome</h4>
    <p><small>用 `for` 檢查一個字串是不是迴文。</small></p>
    <h4>7. Check if a postation account </h4>
    <p><small>計算一個郵局帳號是不是符合規則。</small></p>
  </div>
</div>

---

多層 `for` 迴圈
----

[[mrorz-js-nestedloop?javascript,console]]

---

`switch` - `case`
-----------

記得 `break;`

[[mrorz-js-switch?javascript,console]]
