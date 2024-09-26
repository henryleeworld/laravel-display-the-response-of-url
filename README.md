# Laravel 11 顯示網址的回應

引入 spatie 的 visit 套件來擴增顯示網址的回應，預設情況下，輸出將用顏色顯示。回應後會顯示回應狀態碼和回應時間。

## 使用方式
- 把整個專案複製一份到你的電腦裡，這裡指的「內容」不是只有檔案，而是指所有整個專案的歷史紀錄、分支、標籤等內容都會複製一份下來。
```sh
$ git clone
```
- 將 __.env.example__ 檔案重新命名成 __.env__，如果應用程式金鑰沒有被設定的話，你的使用者 sessions 和其他加密的資料都是不安全的！
- 當你的專案中已經有 composer.lock，可以直接執行指令以讓 Composer 安裝 composer.lock 中指定的套件及版本。
```sh
$ composer install
```
- 產生 Laravel 要使用的一組 32 字元長度的隨機字串 APP_KEY 並存在 .env 內。
```sh
$ php artisan key:generate
```
- 執行 __visit__ 指令來瀏覽指定網址。
```sh
$ visit {網址}
```

----

## 畫面截圖
![](https://i.imgur.com/v8PjAO7.png)
> 避免顯示回應，只顯示回應結果區塊
