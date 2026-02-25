# Iteration 011 - 腦機介面教學頁

## 主題
腦機介面（神經訊號解碼與臨床應用）

## 產出檔案
- `bci_neural_decoding_guide.html`

## 本輪升級
- 新增互動元件：**BCI 路線選型模擬器**
  - 可調整訊號解析度需求、侵入性容忍度、即時控制需求
  - 即時輸出建議的 BCI 技術路線
- 延續 YouTube 嵌入穩定性策略：
  - `youtube-nocookie` 嵌入
  - 補齊 `enablejsapi`、`origin`、`widget_referrer`
  - 每支影片附直接開啟 YouTube 的回退連結

## 影片清單（已驗證）
1. `6QcY7v9Kio4` - DW Shift - *Brain-Computer Interface: With These Devices You Can Control Machines with Your Mind | BCI explained*
2. `bwriLGRuDZI` - College of Engineering, Carnegie Mellon University - *Bin He: EEG-Based, Non-Invasive Brain-Computer Interface Advancement*
3. `iTZ2N-HJbwA` - UC San Francisco (UCSF) - *How a Brain Implant and AI Gave a Woman with Paralysis Her Voice Back*
4. `Gv_XB6Hf6gM` - WIRED - *The Science Behind Elon Musk’s Neuralink Brain Chip*
5. `7hUmDk-BvCo` - Rice Ken Kennedy Institute - *Chethan Pandarinath, PhD - AI-Powered Intracortical Brain-Computer Interfaces*

## 開啟方式（避免錯誤 153）
請用本機 HTTP 伺服器開啟，不要直接雙擊檔案（`file://`）：

```bash
python -m http.server 5500
```

然後在瀏覽器打開：

```text
http://localhost:5500/outputs/iteration_011/bci_neural_decoding_guide.html
```
