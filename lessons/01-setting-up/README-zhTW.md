# 建置專案
首先，我們需要安裝[Node.js](https://nodejs.org)以及套件管理裝置[npm](https://www.npmjs.com/).

當我們已經完成上述的環境安裝後，我們可以開始使用command line來建置這個專案。

## 複製專案至本機

```
git clone https://github.com/reactjs/react-router-tutorial
cd react-router-tutorial
cd lessons/01-setting-up
npm install
npm start
```

使用瀏覽器開啟這個網址 [http://localhost:8080](http://localhost:8080)

你可以參考在這個專案中的程式碼、我們如何使用webpack以及npm scripts來執行這個app的。

開啟瀏覽器後，應該可以看到 "Hello React Router" 這樣的字樣呈現。

## 進行改動
打開 `modules/App.js` 檔案，然後更動其中的文字，例如，你可以改成"Hello
<your name>"，此時，瀏覽器所顯示的字樣會根據你所改動的程式碼自動重新整理。


---

[Next: Rendering a Router](../02-rendering-a-route/)
