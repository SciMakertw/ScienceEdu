# Iteration 013 - 海水淡化與水資源工程教學頁

## 主題
海水淡化與水資源工程（Desalination & Water Infrastructure）

## 產出檔案
- `desalination_water_engineering_guide.html`

## 本輪升級
- 新增互動元件：**供水組合模擬器**
  - 可調整乾旱壓力、能源成本、再生水能力
  - 即時輸出供水策略優先順序
- 延續 YouTube 嵌入穩定性策略：
  - `youtube-nocookie` 嵌入
  - 補齊 `enablejsapi`、`origin`、`widget_referrer`
  - 每支影片附直接開啟 YouTube 的回退連結

## 影片清單（已驗證）
1. `mxqOPdEUNTs` - Practical Engineering - *Why Is Desalination So Difficult?*
2. `B13tffiuLLM` - SydneyWaterTV - *What is Desalination and why do we use it?*
3. `mEXzzlDCkoo` - Water Corporation - *What happens at a Seawater Desalination Plant | Our water world*
4. `wYkkLUckmg4` - MIT Mechanical Engineering - *Electrodialysis Explained*
5. `GgKi2x9od_0` - DW Planet A - *How Singapore solved its looming water crisis*

## 開啟方式（避免錯誤 153）
請用本機 HTTP 伺服器開啟，不要直接雙擊檔案（`file://`）：

```bash
python -m http.server 5500
```

然後在瀏覽器打開：

```text
http://localhost:5500/outputs/iteration_013/desalination_water_engineering_guide.html
```
