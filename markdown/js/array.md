購物清單
-------

<div class="row">
    <div class="span3">
        ![Shopping list](images/js/shopping_list.jpg)
        <small>[圖片來源 - hobvias sudoneighm](http://www.flickr.com/photos/striatic/159109141/)</small>
    </div>
    <div class="span3">
        <h3>「列表」</h3>
        <ul>
            <li>沒有明確的 key</li>
            <li>有順序性</li>
        </ul>
    </div>
</div>

<!-- Platforms 0 to 8 http://scalingmountlu.com/2013/03/ -->

---

用陣列呈現列表
-------------

![多層櫃](images/programming/numbered-drawer.jpg)

[圖片來源](http://www.bigstockphoto.com/zh/image-4195122/stock-photo-antique-wooden-medicine-cabinet-with-numbered-drawers-and-white-knobs)

會自動編號（有順序）的多層櫃

---

建立陣列
----------

[[qihez?js,console]]

用中括號 `shoppingList[N]` 來拿到第 N 個要買的東西，N 從 0 開始算。

---

陣列實字 Array Literal
-------

```js
var shoppingList = ["布料", "棋盤", "稿紙", "綠豆糕"];
```

以上陣列實字，和下面等價

```js
var shoppingList = [];
shoppingList.push("布料");
shoppingList.push("棋盤");
shoppingList.push("稿紙");
shoppingList.push("綠豆糕");
```

---

操作陣列
-----------

若有個字串變數名叫 `list`……

* `list[位置]`：取得此位置的元素（位置從 0 起算）
* `list.length`：長度
* `list.indexOf(元素)`：元素在陣列的位置（從左邊數來）
* `list.slice(位置)`：切陣列

[[lojux?javascript,console]]

[陣列可以用的 Method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)很像字串。

---

LearnStreet 練習時間
--------

「Arrays」的[練習連結](http://www.codecademy.com/courses/javascript-beginner-en-8j9pu/3/1)

![Lean street If](images/js/code-array.png)

約需 18 分鐘。


---

<div class="row">
  <div class="span3">
    <h4>1. Every Other One</h4>
    <p><small>把第 0、2、…個元素加總</small></p>
    <h4>2. Pushing Arrays</h4>
    <p><small>產生 `[1,2,…,n]`</small></p>
    <h4>3. Reverse Swapping</h4>
    <p><small>把整個陣列排序反過來</small></p>
  </div>
  <div class="span3">
    <h4>6. Delete Free Emails</h4>
    <p><small>將 `eMails` 中字串含有 `"free"` 的字串整個替代為 `"spam"`</small></p>
    <h4>7. Sum up different type data in array</h4>
    <p><small>運用 `if` 判斷array中不同類型的值的總和。</small></p>
    <h4>7. Sum up different type data in Object</h4>
    <p><small>實作一個候選人得票加總器，輸出一個 Object 存放大家的票數。</small></p>
  </div>
</div>