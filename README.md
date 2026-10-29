# 生物統計學作業與實習成果專案 (Biostatistics Coursework & Lab Portfolio)

本儲存庫收錄大學三年級上學期**生物統計學**之各項實習專案、分析報告與作業成果。內容涵蓋臨床數據統計檢定、SPSS 與 Python 雙軌交叉驗證、無母數統計分析、流行病學異常事件調查及完整專案技術移轉手冊。

---

## 📌 專案與研究主題概述

### 1. 臨床健康數據統計分析與視覺化（DM 專案）
- **核心資料集**：`DM.xls`（臨床代謝健康指標量測資料）
- **研究設計**：單一因子實驗設計（Single-Factor Design），以「組別（Group 1 vs. Group 2）」為自變數。
- **應變數分析**：
  - **血糖 (Blood Glucose, mg/dL)**：評估胰島素調節機能與組別差異。
  - **收縮壓 (Systolic Blood Pressure, mmHg)**：評估心血管生理指標差異。
  - **身體質量指數 (BMI, kg/m²)**：評估代謝體位與肥胖分佈。
- **統計方法學**：
  - 常態性檢定（Shapiro-Wilk Test）
  - 變異數齊一性檢定（Levene's Test）
  - 獨立樣本 $t$ 檢定（Student's $t$ / Welch's $t$-test）
  - 曼-惠特尼 $U$ 檢定（Mann-Whitney $U$ Test）
  - 效應量評估（Cohen's $d$ / Hedges' $g$）
  - Seaborn / Matplotlib 科研級箱型圖與分佈視覺化

### 2. 生物統計實習成果移轉暨 SPSS / Python 雙軌驗證
- **研究主題**：
  - **腫瘤醫學生物標記**：乳癌（BC）與肺腺癌（LUAD）之 HER2 表現量差異分析（Mann-Whitney $U$ 檢定）。
  - **職業運動員年薪分析**：多群組無母數單因子分析（Kruskal-Wallis $H$ 檢定）與事後多重比較（Bonferroni 校正）。
- **雙軌驗證特色**：
  - 嚴格比對 IBM SPSS 統計輸出報表與 Python SciPy/Statsmodels 計算數值（等級秩和、檢定統計量 $U$、$Z$ 值、漸近/精確雙尾 $p$ 值）。
  - 數值一致性達 100% 完全對齊，並建置高規格技術交接手冊與排版。

### 3. 流行病學調查報告：橘郡異常事件調查（SPSS）
- 針對特定群聚/異常公共衛生事件進行個案流行病學調查。
- 運用交叉分析表、卡方檢定（Chi-Square Test）及勝算比（Odds Ratio, OR）評估潛在危險因子與事件關聯性。

### 4. 基礎統計實習演練
- 投籃實驗（二項分佈 Binomial Distribution、機率分配模式）。
- 代謝數據推論統計各階段課堂作業。

---

## 📂 檔案架構與目錄導覽

| 檔案名稱 | 格式 | 說明 |
| :--- | :---: | :--- |
| `DM_專案交接手冊.docx` | Word | 代謝健康數據組別差異檢定、推論模型與視覺化之完整技術交付手冊 |
| `生統實習_統計分析移轉與SPSS雙軌驗證交接手冊.pdf` | PDF | SPSS 原始輸出與 Python 雙軌驗證比對手冊（含方法論與圖表） |
| `橘郡異常事件調查報告-113007003-蘇芸晞.pdf` | PDF | 流行病學與公共衛生異常事件統計調查報告 |
| `生統作業 1001 DM 113007003 蘇芸晞.pdf` | PDF | 臨床健康指標組別差異分析階段作業 |
| `生物統計學 1001 投籃 113007003 蘇芸晞.pdf` | PDF | 二項分佈與投籃機率模型實作報告 |
| `生統作業 113007003 蘇芸晞.pdf` | PDF | 生物統計推論檢定學期個人作業 |
| `.gitignore` | 設定檔 | Git 版本控制過濾規則 |

---

## 🛠️ 分析工具與技術棧 (Tech Stack)

- **統計分析軟體**：IBM SPSS Statistics
- **程式語言與環境**：Python 3 (pandas, numpy, scipy, statsmodels)
- **資料視覺化**：Seaborn, Matplotlib
- **文件與報告編撰**：Microsoft Word, LaTeX / Markdown, Adobe PDF

---

## 👤 作者資訊

- **作者**：蘇芸晞 (Yun-Hsi Su)
- **學號**：113007003
