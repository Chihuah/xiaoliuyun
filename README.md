# 小六壬占卜網頁

這是一個基於「小六壬」占卜方法的簡單靜態網頁，能夠根據使用者輸入的農曆月份、日子和時辰計算吉凶狀態。該網頁使用 HTML、CSS 和 JavaScript，並搭配 [LunarSolarConverter](https://github.com/isee15/Lunar-Solar-Calendar-Converter) 函式庫來自動帶入當前日期的農曆資訊與中國時辰。

## 功能特色

- **小六壬占卜算法**：依據輸入的農曆月份、日子和時辰計算結果，最終結果會是「大安」、「留連」、「速喜」、「赤口」、「小吉」或「空亡」其中之一。
- **自動預設當前日期與時辰**：利用 LunarSolarConverter 函式庫將當前公曆日期轉換成農曆，並根據系統時間自動選擇對應的中國時辰。
- **響應式設計**：網頁採用 CSS Flexbox 設計，適合各種裝置（桌面、平板、手機）瀏覽。
- **簡單易用**：只需打開網頁、確認預設值或自行修改，再點擊按鈕即可進行占卜。
- **多種占卜模式**：提供「簡答」、「問事」、「深解」三種模式，可依需求切換，並得到相應的結果解釋。

## 使用說明

1. **自動帶入預設值**  
   當網頁載入時，農曆月份、日子與時辰會根據當前系統日期自動填入。
2. **修改與占卜**
   如有需要，你可以修改輸入數值，並在「占卜模式」中選擇「簡答」、「問事」或「深解」。
   點擊「開始占卜」後，網頁會依所選模式計算並顯示對應的結果解釋。

## 技術細節

- **前端技術**：HTML、CSS、JavaScript。
- **日期轉換**：使用 [LunarSolarConverter](https://github.com/isee15/Lunar-Solar-Calendar-Converter) 函式庫將公曆轉換為農曆。
- **時辰判斷**：根據系統時間自動對應中國傳統十二時辰。

## 相關參考網頁

1. [小六壬掐指占卜法](http://www.lukyam.com/04/04b_91.htm)
2. [掐指占卜法——小六壬](https://blog.udn.com/guccitao/180374186)
3. [銅口亂斷| 小六壬| 命理| 程式](https://vocus.cc/article/63a6db7dfd897800013450e8)
4. [小六壬占卜法的源流、原理與現代詮釋 (Perplexity Deep Research)](https://www.perplexity.ai/search/qing-yan-jiu-yi-zhong-xuan-xue-aOENdRW_Q4yWG9HcwJZB5Q)
5. [倪海廈，如何占卜 (Youtube)](https://www.youtube.com/watch?v=1KYhDGldkt4&t=48s)

## 免責聲明

此占卜結果僅供參考或娛樂使用，請勿過度依賴或迷信。

## 貢獻

歡迎對此專案提出建議或改進。如有疑問，請在 GitHub 上提交 Issue 或 Pull Request。

## 授權

本專案採用 [MIT License](LICENSE) 授權，詳情請參閱 LICENSE 文件。
