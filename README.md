# 2027 福爾摩沙礦物博覽會聯合參展提案

以 `Formosa_2027_Editable_2.pptx` 為內容依據的單頁靜態網站。保留修正版品牌文案、作品照片及獲獎資訊，支援手機排版與圖片放大。

## 本機預覽

直接以瀏覽器開啟 `index.html` 即可，無須安裝套件。也可在本資料夾執行 `python -m http.server 8000`，瀏覽 `http://localhost:8000`。

## 上傳 GitHub Pages

1. 建立自己的 GitHub 儲存庫（使用免費帳號時可選 Public）。
2. 將本資料夾的**內容**上傳至儲存庫根目錄，讓 `index.html` 直接位於根目錄；不要只上傳 ZIP，也不要多包一層資料夾。保留 `assets` 子目錄與檔名。
3. 到儲存庫的 **Settings → Pages**。
4. 在 **Build and deployment → Source** 選 **Deploy from a branch**。
5. 分支選 `main`（或實際上傳的分支），資料夾選 **/(root)**，按 **Save**。
6. 部署完成後，Pages 設定頁會顯示公開網址，通常為 `https://你的帳號.github.io/儲存庫名稱/`。

日後修改並提交同一分支的檔案，GitHub Pages 會重新部署。此交付檔案尚未推送至任何遠端儲存庫，也尚未部署。

官方操作文件：https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 修改內容

- `index.html`：品牌介紹、日期、參展構想及社群連結。
- `styles.css`：顏色、字級、版面、手機與列印樣式。
- `script.js`：圖片放大視窗，支援 Esc 關閉及鍵盤焦點回復。
- `assets/`：從修正版 PPTX 擷取的品牌照片、獎狀及圖示。
- `.nojekyll`：停用 Jekyll 處理，供靜態部署使用。

所有網頁資源均使用相對路徑，無遠端字型、分析追蹤、第三方套件或後端服務。停用 JavaScript 時圖片連結仍可開啟原圖。

## 內容與圖片

目前內容是「聯合參展提案」，未宣稱參展已獲核准。若後續要改成面向消費者的正式參展公告，請確認主辦核准、攤位資訊後，再調整提案及報名段落。

獎項以提供之獎狀為準：Hank Lu，2020 USFG Single Stone Competition，Novice Division，新手組第二名，分數 99.5752。照片與作品權利歸原權利人，本專案未另行授予第三方使用授權。
