# Iteration 014 - 電網儲能與調度教學頁

## 主題
電網儲能與調度（Grid Storage & Dispatch）

## 產出檔案
- `grid_storage_dispatch_guide.html`

## 本輪升級
- 新增互動元件：**調度策略模擬器**
  - 可調整再生能源波動、儲能時長、尖峰負載壓力
  - 即時輸出調度策略優先順序
- 延續 YouTube 嵌入穩定性策略：
  - `youtube-nocookie` 嵌入
  - 補齊 `enablejsapi`、`origin`、`widget_referrer`
  - 每支影片附直接開啟 YouTube 的回退連結

## 影片清單（已驗證）
1. `4L31dHXP6i0` - EPCEenergyeducation - CAEL - *The Smart Grid Explained - An Understanding for Everyone*
2. `9eAFEU7pMwU` - Student Energy - *Energy Storage 101*
3. `E-m7Psbuup0` - saVRee - *How Pumped Storage Power Plants Work (Hydropower)*
4. `UWsAo46PUMU` - Australian Renewable Energy Agency (ARENA) - *Demand response - Flow Power*
5. `7G4ipM2qjfw` - Practical Engineering - *Connecting Solar to the Grid is Harder Than You Think*

## 開啟方式（避免錯誤 153）
請用本機 HTTP 伺服器開啟，不要直接雙擊檔案（`file://`）：

```bash
python -m http.server 5500
```

然後在瀏覽器打開：

```text
http://localhost:5500/outputs/iteration_014/grid_storage_dispatch_guide.html
```
