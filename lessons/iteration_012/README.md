# Iteration 012 - 碳捕捉與封存（CCS）教學頁

## 主題
碳捕捉與封存（CCS，Carbon Capture and Storage）

## 產出檔案
- `ccs_learning_guide.html`

## 本輪升級
- 新增互動元件：**CCS 方案選型儀表板**
  - 可調整排放端 CO₂ 濃度、儲層距離、政策支持度
  - 即時輸出優先部署策略
- 延續 YouTube 嵌入穩定性策略：
  - `youtube-nocookie` 嵌入
  - 補齊 `enablejsapi`、`origin`、`widget_referrer`
  - 每支影片附直接開啟 YouTube 的回退連結

## 影片清單（已驗證）
1. `XxjNhLZCae0` - Freethink - *Carbon Capture Technology Explained | Seachange*
2. `I5eFPBD04FY` - SLB - *How Carbon Storage Works | CCS & CCUS Explained*
3. `7j3OTLmaE-g` - British Geological Survey - *Carbon capture and storage research at the British Geological Survey*
4. `1rAR7PSLUHY` - Climeworks - *How does direct air capture remove CO₂?*
5. `q61e2r8g4dc` - MIT Energy Initiative - *Rethinking carbon capture and sequestration*

## 開啟方式（避免錯誤 153）
請用本機 HTTP 伺服器開啟，不要直接雙擊檔案（`file://`）：

```bash
python -m http.server 5500
```

然後在瀏覽器打開：

```text
http://localhost:5500/outputs/iteration_012/ccs_learning_guide.html
```
