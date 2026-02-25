# Iteration 010 - 半導體製程教學頁

## 主題
半導體製程（晶片製造與良率工程）

## 產出檔案
- `semiconductor_fabrication_guide.html`

## 本輪升級
- 新增互動元件：**良率-成本決策儀表板**
  - 可調整缺陷密度、遮罩複雜度、交期壓力
  - 即時輸出建議優先改善策略
- 延續 YouTube 嵌入穩定性策略：
  - `youtube-nocookie` 嵌入
  - 補齊 `enablejsapi`、`origin`、`widget_referrer`
  - 每支影片附直接開啟 YouTube 的回退連結

## 影片清單（已驗證）
1. `IkRXpFIRUl4` - TED-Ed - *How are microchips made?*
2. `Bu52CE55BN0` - Samsung Semiconductor Newsroom - *Semiconductor Manufacturing Process Explained*
3. `5a8xjH2tOkM` - Texas Instruments - *300mm wafer fab virtual tour*
4. `RI3lCUEzSvE` - IBM Research - *How EUV lithography works*
5. `B2482h_TNwg` - Branch Education - *The $200M Machine that Prints Microchips*

## 開啟方式（避免錯誤 153）
請用本機 HTTP 伺服器開啟，不要直接雙擊檔案（`file://`）：

```bash
python -m http.server 5500
```

然後在瀏覽器打開：

```text
http://localhost:5500/outputs/iteration_010/semiconductor_fabrication_guide.html
```
