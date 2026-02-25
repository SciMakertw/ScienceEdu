# 迭代 001 成果說明

## 主題
CRISPR 基因編輯：從分子機制到應用與倫理

## 產出檔案
- `crispr_learning_guide.html`

## 內容摘要
- 5 個章節的敘事式科普教學
- 每章節嵌入 1 支 YouTube 教學影片
- 每支影片附「老師解讀」段落
- 單頁 HTML，含導覽、閱讀進度條、滾動顯示動畫、響應式版面

## 使用影片（已驗證 YouTube ID）
1. `6tw_JVz_IEc` - TED-Ed
2. `Aqw4DihmoQY` - Innovative Genomics Institute – IGI
3. `_L-t7Esup6s` - SciShow
4. `4YKFw2KZA5o` - nature video
5. `47pkFey3CZ0` - Innovative Genomics Institute – IGI

## 驗收結果
- 已完成首輪可交付教學頁
- 成果依規則存放於獨立資料夾 `outputs/iteration_001/`

## 開啟方式（避免 YouTube 錯誤 153）
- 不要直接雙擊 HTML（`file://` 可能讓 YouTube 嵌入失敗）
- 請在專案根目錄執行：
  - `python -m http.server 5500`
- 再用瀏覽器開啟：
  - `http://localhost:5500/outputs/iteration_001/crispr_learning_guide.html`
- 若仍出現 153：
  - 關閉會移除 `Referer` 的隱私設定或外掛（例如 Brave Shields、Referrer 控制外掛）
  - 改用 Chrome/Edge 無痕模式（不載入外掛）快速驗證
