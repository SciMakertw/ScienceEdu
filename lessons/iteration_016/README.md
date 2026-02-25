# Iteration 016 - 量子通訊與 QKD 教學頁

## 主題
量子通訊與量子密鑰分發（QKD）工程實務

## 產出檔案
- `quantum_qkd_guide.html`

## 本輪升級
- 新增互動元件：**QKD 佈建決策器**
  - 可調整光纖損耗壓力、鏈路距離需求、合規要求
  - 即時輸出部署優先策略
- 延續 YouTube 嵌入穩定性策略：
  - `youtube-nocookie` 嵌入
  - 補齊 `enablejsapi`、`origin`、`widget_referrer`
  - 每支影片附直接開啟 YouTube 的回退連結

## 影片清單（已驗證）
1. `m6SIOLL_Cio` - Department for Science, Innovation and Technology - *PhD student explains Quantum Communications*
2. `R0SOqLwLOR0` - Qiskit - *Outsmarting Hackers: Quantum Key Distribution Explained*
3. `D7ld4fVq7VE` - Centre for Quantum Technologies - *Quantum Key Distribution*
4. `4QlcKuxDGrs` - Science Magazine - *Quantum satellite achieves 'spooky action' at record distance*
5. `uE_Y1C4QPU8` - National Institute of Standards and Technology - *Post-Quantum Cryptography: the Good, the Bad, and the Powerful*

## 開啟方式（避免錯誤 153）
請用本機 HTTP 伺服器開啟，不要直接雙擊檔案（`file://`）：

```bash
python -m http.server 5500
```

然後在瀏覽器打開：

```text
http://localhost:5500/outputs/iteration_016/quantum_qkd_guide.html
```
