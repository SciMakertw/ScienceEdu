# Iteration 015 - 低軌衛星通訊教學頁

## 主題
低軌衛星通訊（LEO constellation 與地面網路整合）

## 產出檔案
- `leo_satcom_guide.html`

## 本輪升級
- 新增互動元件：**星座設計模擬器**
  - 可調整衛星密度、地面閘道密度、終端流量壓力
  - 即時輸出部署優先策略
- 延續 YouTube 嵌入穩定性策略：
  - `youtube-nocookie` 嵌入
  - 補齊 `enablejsapi`、`origin`、`widget_referrer`
  - 每支影片附直接開啟 YouTube 的回退連結

## 影片清單（已驗證）
1. `sN3QNrax8Io` - EUMETSAT - *What’s the difference between GEO/LEO satellites?*
2. `1tw4SmS4Pc4` - Iain Explains Signals, Systems, and Digital Comms - *LEO Satellite Networks: Brief Introduction to Communications Challenges*
3. `qs2QcycggWU` - Branch Education - *How does Starlink Satellite Internet Work?*
4. `REzA_SYInvc` - Eutelsat OneWeb - *How OneWeb's Connectivity Works*
5. `giQ8xEWjnBs` - Real Engineering - *Why SpaceX is Making Starlink*

## 開啟方式（避免錯誤 153）
請用本機 HTTP 伺服器開啟，不要直接雙擊檔案（`file://`）：

```bash
python -m http.server 5500
```

然後在瀏覽器打開：

```text
http://localhost:5500/outputs/iteration_015/leo_satcom_guide.html
```
