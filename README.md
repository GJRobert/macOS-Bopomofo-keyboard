# macOS Bopomofo keyboard
簡單的 macOS 鍵盤，一鍵輸入[注音符號](https://www.wikiwand.com/zh-tw/注音符號)。
* 鍵位排列：大千式
* 含空白鍵

## 前言
這是很簡單的 Ukelele 小習作（Windows 平台也有類似工具）， 煞有介事地放到 GitHub 上也真好笑， 不過既然做了，就還是分享出來，也許有人看了就 fork 做更好的東西， 或是激發有人做其他東西的靈感， 或至少有朋友像我一樣可以用這個鍵盤輕鬆輸入注音文 XD

## 緣起
因為我自己並不使用注音類的輸入法，所以要輸入注音符號時， 還得透過嘸蝦米輸入法拆碼，一個「ㄤ」也要 4 碼（,ang） 但注音符號明明就長在鍵盤上，一鍵一個豈不輕鬆。 所以就單獨做了這麼一個鍵盤。它不是輸入法，不是用來輸入漢字， 但可以輕鬆輸入注音符號。

## 安裝方法
### 自動
1. 下載[最新版本](https://github.com/GJRobert/macOS-Bopomofo-keyboard/releases/latest)的 .dmg
2. 掛載 .dmg 後，雙擊 `Keyboard Installer`
3. 將 .dmg 內的 `Bopomofo.bundle` 拖入剛才開啟好的 Keyboard Installer 小程式（確認 `Bopomofo` 有填入 `Keyboard Layout to install:` 下方），然後雙擊左邊的一個黑人或是右邊的一群黑人（安裝給目前使用者還是這台電腦的全部使用者）
4. 開啟鍵盤偏好設定，加入`中文（注音符號）`語言中的 `Bopomofo`（帶有洋紅色「ㄅㄆㄇㄈ」圖示）

### 手動
1. 下載[最新版本](https://github.com/GJRobert/macOS-Bopomofo-keyboard/releases/latest)的 .zip
2. 解壓縮後，將 `Bopomofo.bundle` 置入 `~/Library/Keyboard Layouts`
3. 開啟鍵盤偏好設定，加入`中文（注音符號）`語言中的 `Bopomofo`（帶有洋紅色「ㄅㄆㄇㄈ」圖示）

### 後續
即可開始使用。

【給多種輸入法/語文鍵盤重度使用者的 tip】可使用 Kawa 小工具，設定一組熱鍵給你常用的輸入法或鍵盤，然後也設定一組熱鍵給 Bopomofo，這樣快速切換到 Bopomofo，打完再馬上切回去。

## Known issues
* 除空白鍵外，暫無其他英數字元

## 銘謝
* [Ukelele: Mac OS X Keyboard Layout Editor (John Brownie)](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele)：極棒的 GUI keyboard 編輯器！

## 解除安裝
1. 開啟鍵盤偏好設定，把 `Bopomofo` 移除
2. 把 `~/Library/Keyboard Layouts` 中的 `Bopomofo.bundle` 刪除或移出
