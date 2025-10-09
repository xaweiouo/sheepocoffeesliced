 # 羊蹄咖啡專題

## 結構說明

```
coffee
├─assests
├───scss
├─────base (通用樣式)
├───────_base.scss (全域通用樣式)
├───────_utils.scss (全域自訂義通用樣式)
├─────customize
├───────_utils.scss (暫時無用)
├───────_variables.scss (自訂義用來覆蓋bootstrap 顏色 間距的scss)
├─────layout (對應header or footer等共用的scss)
├───────_footer.scss (footer scss)
├───────_header.scss (header scss) 
├─────pages (對應個頁面的scss)
├───────about.scss (關於羊蹄 scss)
├───────explore.scss (探索羊蹄 scss)
├───────index.scss (首頁專用的scss)
├───────productdetail.scss (產品詳情頁 scss)
├───────products.scss (線上商店 scss)
├─────utils (暫時無用)
├───────_variables-dark.scss  
├───────_variables.scss  
├───all.scss (所有import的scss)
├─layout (ejs)
├───footer.ejs (footer程式碼)
├───header.ejs (header程式碼)
├───js.ejs (所有javascript )
├───style.ejs (所有額外參考css)
├─pages (html)
├───about.html (關於羊蹄)
├───demo.html (通用樣式demo用)
├───explore.html (探索羊蹄)
├───index.html (首頁)
├───productdetail.html (產品詳情頁)
├───products.html (線上商店)
├─public (靜態不編譯檔案)
├───fonts (字體)
├─────ChenYuluoyan-2.0-Thin.woff2
├───images (靜態圖片)

```

