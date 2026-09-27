# 釜山旅行手帳 v1.1

直接開啟 `index.html` 預覽。HTML 與 assets 資料夾需保持相同相對位置。

## GitHub Pages 部署檔案

將本資料夾「裡面的檔案」放入準備作為網站來源的目錄：

```text
index.html
.nojekyll
assets/
  busan-cover-v1.1.png
```

這是純靜態網站，不需 npm、建置指令、API 金鑰或後端。圖片採相對路徑，可用於 GitHub Pages 的專案子路徑。

## 更新

- 移除原始筆記展開區塊及內嵌全文。
- 加入 imagegen 生成的釜山海岸意象插畫。
- 保留每日行程、地圖搜尋、列印與行前清單。

行前清單儲存在目前瀏覽器的 localStorage；本機預覽與部署網站的勾選狀態不會互相同步。
封面為 AI 意象插畫，非景點實拍。原始 v1.0 與文字筆記不在本部署包內。
