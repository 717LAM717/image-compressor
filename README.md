# JPG Photos Under 2MB

這是一個純前端 JPG 批次壓縮工具，適合網拍照片上架前使用。

## 功能

- 批次選取或拖曳 JPG / JPEG 照片
- 將每張照片壓縮到指定 MB 以下，預設為 2MB
- 維持原始照片比例
- 壓縮完成後產生 ZIP 檔下載
- 所有處理都在瀏覽器內完成，照片不會上傳到伺服器

## 使用方式

直接開啟 `index.html`，或部署到 GitHub Pages 後用網址開啟。

## GitHub Pages 部署

1. 在 GitHub 建立一個新的 repository。
2. 上傳 `index.html`、`README.md`、`.nojekyll`。
3. 到 repository 的 Settings -> Pages。
4. Source 選 `Deploy from a branch`。
5. Branch 選 `main`，資料夾選 `/root`。
6. 儲存後等待 GitHub 產生網址。

## 注意

如果瀏覽器阻擋自動下載，請在壓縮完成後手動按畫面上的「下載 ZIP」按鈕。
