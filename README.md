# 2105 正新橡膠｜技術分析報告（OHLCV × Indicators）

## 專案摘要 | Overview
本專案針對 **2105 正新橡膠** 進行技術面分析，整合 OHLCV 價量資料並計算常用技術指標（MA、RSI、OBV、NATR），輸出可重用的資料檔（CSV）與可視化報告（HTML），用於快速掌握趨勢、動能與波動風險。
  
This project delivers a technical analysis report for **2105 Maxxis**, combining OHLCV price/volume data with key indicators (MA, RSI, OBV, NATR). It outputs reusable datasets (CSV) and a shareable HTML report to support trend, momentum, and volatility interpretation.

---

## 分析內容 | What’s inside
- **OHLCV 資料整理**：開高低收與成交量的基本檢視與清理  
  OHLCV preparation: basic cleaning and sanity checks
- **趨勢指標（Trend）**：移動平均線 **MA(5/20)**（可依你的設定調整）  
  Trend: Moving Averages **MA(5/20)** (adjustable)
- **動能指標（Momentum）**：**RSI** 判讀超買/超賣與轉折訊號  
  Momentum: **RSI** for overbought/oversold signals
- **量能指標（Volume）**：**OBV** 量價背離與資金流向輔助判讀  
  Volume: **OBV** to assess price–volume confirmation/divergence
- **波動風險（Volatility）**：**NATR**（Normalized ATR）衡量相對波動程度  
  Volatility: **NATR** (Normalized ATR) for relative volatility/risk

---

## 產出物 | Deliverables
- `2105正新橡膠.html`：完整可視化分析報告（HTML）  
  Full visual report (HTML)
- （若有）`*.csv`：整理後的 OHLCV 與指標資料，可重複利用於回測/視覺化  
  Cleaned OHLCV + indicators for reuse

> 建議：若你想用 GitHub Pages 直接展示，把 HTML 改名為 `index.html` 會最方便。

---

## 如何查看報告 | How to view
### 方式 A：直接下載在本機開啟（最穩）
1. 點進 HTML 檔 → 右上角 **Download**
2. 用 Chrome / Safari 開啟

### 方式 B：GitHub Pages 線上展示（作品集推薦）
1.（建議）將 `2105正新橡膠.html` 改名為 `index.html`
2. Repo → **Settings → Pages**
3. Source：**Deploy from a branch**
4. Branch：`main` / Folder：`/(root)` → Save  
完成後會得到網址：`https://<username>.github.io/<repo>/`

---

## 使用情境 | Use cases
- 快速掌握價格趨勢與多空結構（MA）  
- 評估短期動能與可能轉折（RSI）  
- 輔助確認量價一致性或背離（OBV）  
- 以相對波動衡量風險與交易環境（NATR）

---

## 作者 | Author
Shu-Yu Lin
