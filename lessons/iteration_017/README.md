# Iteration 017 - 工業數位孿生與預測維護教學頁

## 主題
工業數位孿生（Digital Twin）與預測維護（Predictive Maintenance）

## 產出檔案
- `digital_twin_predictive_maintenance_guide.html`

## 本輪升級
- 新增互動元件：**維護策略排程器**
  - 可調整停機成本壓力、資料品質、備品交期壓力
  - 即時輸出維護優先策略
- 延續 YouTube 嵌入穩定性策略：
  - `youtube-nocookie` 嵌入
  - 補齊 `enablejsapi`、`origin`、`widget_referrer`
  - 每支影片附直接開啟 YouTube 的回退連結

## 影片清單（已驗證，6 支）
1. `2hnoGo27uf8` - IBM Technology - *What is a Digital Twin?*
2. `2_o1SDy6__U` - RealPars - *Predictive Maintenance Explained*
3. `ObGhB9CCHP8` - Siemens Knowledge Hub - *Why digital twins will be the backbone of industry in the future*
4. `JHKNZWcfvms` - GE Vernova - *Catch Equipment Failures Early - SmartSignal Predictive Maintenance*
5. `p-q6I_CdWVk` - MIT Open Learning - *What is a digital twin?*
6. `H9uaBg1dsNQ` - BMW Group - *Predictive Maintenance at the BMW iFACTORY*

## 開啟方式（避免錯誤 153）
請用本機 HTTP 伺服器開啟，不要直接雙擊檔案（`file://`）：

```bash
python -m http.server 5500
```

然後在瀏覽器打開：

```text
http://localhost:5500/outputs/iteration_017/digital_twin_predictive_maintenance_guide.html
```
