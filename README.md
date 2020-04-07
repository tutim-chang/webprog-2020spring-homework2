# 作業二：保存狀態

## 作業

這個作業中，您將嘗試保存**瀏覽狀態**。

在頁面中儲存變數值到 ```SESSION``` ，並在瀏覽其他頁面時，從 ```SESSION``` 取回該值。

您將使用以下語法：

```php
session_start();
```

您將使用以下語法保存「值」到 SESSION 中，並命名為「鍵值」：

```php
$_SESSION['鍵值'] = 值;
```

您將使用以下語法由 SESSION 中取為名稱為「鍵值」的 SESSION 值：
```php
$v = $_SESSION['鍵值']
```

請依照作業範例進行製作。

作業中程式碼將包括 [demo2-1a.php](demo2-1a.php) 與 [demo2-1b.php](demo2-1b.php) 表示不同頁面，以及 [demo2-1c.php](demo2-1c.php) 作為編輯名稱使用。

範例中 [images/icons8-edit-26.png](images/icons8-edit-26.png) 檔案為 ![images/icons8-edit-26.png](images/icons8-edit-26.png) 圖檔，檔案來自 [icons8](https://icons8.com/) ，您可依照其授權規則使用。

除了用 SESSION 保存狀態之外，在不同頁面間保存（或傳遞）狀態還可以使用「網址中的查詢字串」（您可以在範例中觀察到），或者透過表單（隱藏）欄位，或者 COOKIE 等技巧來進行。您可以探究其特性後，適當應用於本作業中。

* 本題需使用 CSS 美化畫面。
* 本題不使用 JavaScript 處理用戶端界面，限制只由伺服器端輸出。


## 分組

本次作業每組 3 ～ 4 人

請在下方條列處寫下名單，條列第一個為組長：

* D07234567 張某某 （組長）
* D07234568 張某某
* D07234567 張某某
* 自行新增


## 繳交

**請由組長繳交**

1. 若沒有 GitHub 帳號，請建立 [GitHub 帳號](https://github.com/join)
    1. 新建帳號請使用稍微正式一點的英文名稱，以後也許可作為作品記錄
    2. 請將帳號名稱 Email 或 LINE 給老師
2. 點選[作業連結](https://classroom.github.com/a/LwUQ3-d8)後，同意```Accept this assignment```後加入作業
    1. 組長加入即可
    2. 若組長換人，新組長必須重新加入作業
    3. 以後每個作業要一次
    4. 你會看到你的作業網址 ```https://github.com/tutim-chang/wp20s-hw1-D07xxxxxx``` 請記好
3. 撰寫作業
    1. 使用 ```git``` 工具 ```clone``` 後取得初始內容
        * ```git clone https://github.com/tutim-chang/wp20s-hw1-D07xxxxxx.git```
    2. 修改你的程式碼，並測試無誤
4. 繳交作業
    1. 使用 ```git``` 工具上傳
        1. ```git add .``` 加入修改過的檔案到版本中
        2. ```git commit -m '修改的提示訊息'``` 提交版本
        3. ```git push``` 上傳版本到 GitHub 中
    5. 可多次繳交，以期限內最後一次上傳為準
    6. 可作為製作中進度的保存與分享
5. ~~DEMO作業~~ 本次作業無需DEMO
6. 與老師討論作業
    1. 在前述作業網址中，可找到```Pull Request```連結，回應(Feedback)在裡面
    2. 急件請使用電話與老師聯繫
7. 放棄繳交
    1. 若你決定放棄本次作業，或者你由組長身分轉跳為它組的組員，可放棄繳交
    2. 請清空上方的分組名單，寫下放棄的理由，並使用步驟 4 的方式上傳，或直接於網站中修改 README.md 檔案。
8. 完成繳交
    1. 期限後自動完成繳交
    2. 若你不在任何分組名單中，分數為 __0__
    3. 若你在 n 個的分組名單中，分數為 __n組平均/n__
