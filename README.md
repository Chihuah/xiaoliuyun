# 小六壬占卜網頁

這是一個基於「小六壬」占卜方法的簡單靜態網頁，能夠根據使用者輸入的農曆月份、日子和時辰計算吉凶狀態。該網頁使用 HTML、CSS 和 JavaScript，並搭配 [solarlunar](https://github.com/6tail/solarlunar) 庫來自動帶入當前日期的農曆資訊與中國時辰。

## 功能特色

- **小六壬占卜算法**：依據輸入的農曆月份、日子和時辰計算結果，最終結果會是「大安」、「留連」、「速喜」、「赤口」、「小吉」或「空亡」其中之一。
- **自動預設當前日期與時辰**：利用 `solarlunar` 庫將當前公曆日期轉換成農曆，並根據系統時間自動選擇對應的中國時辰。
- **響應式設計**：網頁採用 CSS Flexbox 設計，適合各種裝置（桌面、平板、手機）瀏覽。
- **簡單易用**：只需打開網頁、確認預設值或自行修改，再點擊按鈕即可進行占卜。

## 使用說明

1. **自動帶入預設值**  
   當網頁載入時，農曆月份、日子與時辰會根據當前系統日期自動填入。  
2. **修改與占卜**  
   如有需要，你可以修改輸入數值。  
   點擊「開始占卜」後，網頁會依據「小六壬」算法計算出最終的占卜結果，並顯示在頁面下方。

## 部署到 GitHub Pages

此專案為純靜態網頁，非常適合部署到 GitHub Pages。部署步驟如下：

1. **建立 GitHub Repository**  
   - 登入 GitHub 並建立一個新的 repository（例如：`xiaoliuyun`）。
   - 將所有檔案（例如 `index.html`、CSS、JavaScript 等）推送到該 repository 的根目錄。

2. **啟用 GitHub Pages**  
   - 進入 repository 的 **Settings** 頁面。
   - 滾動到 **Pages** 區塊。
   - 在 **Source** 下拉選單中，選擇 `main branch`（或你存放檔案的分支），並選擇 `/(root)` 資料夾。
   - 點擊 **Save** 保存設定後，GitHub Pages 會提供一個網址，例如 `https://<你的GitHub使用者名稱>.github.io/<repository名稱>/`。

3. **存取網站**  
   使用瀏覽器開啟 GitHub Pages 提供的網址，即可看到你的占卜網頁。

## 技術細節

- **前端技術**：HTML、CSS、JavaScript。
- **日期轉換**：使用 [solarlunar](https://github.com/6tail/solarlunar) 庫將公曆轉換為農曆。
- **時辰判斷**：根據系統時間自動對應中國傳統十二時辰。

## 貢獻

歡迎對此專案提出建議或改進。如有疑問，請在 GitHub 上提交 Issue 或 Pull Request。

## 授權

本專案採用 [MIT License](LICENSE) 授權，詳情請參閱 LICENSE 文件。
