# 謝向嶸

**Python · 資料整合 · AI 應用工程**

我專注把資料處理、資料庫、API 與使用者介面整合成可驗證、可維護、可交接的系統。目前作品涵蓋海洋動態資料、QGIS／PostGIS、自動化市場研究、Unity／C#、Python／PyTorch 生成模型、Web 應用，以及 Codex Agent Skills 工作流。

## 精選作品

### [S-111 海流品質監測與視覺化系統](https://github.com/steven65026502/QGIS-S111-Viewer)

在 QGIS 中讀取與呈現 S-111 海流資料，整理品質監測結果，並提供前端可串接的 API 與交接文件。

`Python` `PyQGIS` `HDF5/NetCDF` `PostgreSQL/PostGIS` `FastAPI` · 包含資料契約、部署與驗證文件

### SEPA 市場研究與決策輔助系統 · [Live Dashboard](https://steven65026502.github.io/sepa-stock-scanner/)

整合台美股資料掃描、規則化風險閘門、分層候選、歷史回測、隔日驗證、排程與靜態發布；本機流程完成後，由 GitHub Actions／Pages 發布公開唯讀工作台。

`Python` `Pandas` `Streamlit` `GitHub Actions/Pages` `Windows Task Scheduler` `Playwright` · 原始碼與策略設定維持私有，公開頁提供系統狀態、研究與驗證結果，不執行下單

### [AI 應用與資料整合學習工作台](https://github.com/steven65026502/interview-trainer) · [Live Demo](https://steven65026502.github.io/interview-trainer/)

將 28 天課程、理解題、模擬面試、進度追蹤與跨裝置同步整合成可操作的響應式 Web 應用。

`HTML` `CSS` `JavaScript` `Cloudflare Workers` · 具輸入驗證、版本化同步、衝突處理、自動測試與 GitHub Actions

### [Voice to Codex 本機語音工作流](https://github.com/steven65026502/voice-to-codex) · [VSIX](https://github.com/steven65026502/voice-to-codex/releases/tag/v0.2.9)

把 Windows 系統聲音或麥克風、GPU Whisper、WebSocket 與 VS Code 側邊欄串成即時逐字稿工具；音訊留在本機，轉錄結果經繁中、術語與雜訊清理後，可複製並開啟 Codex 繼續處理。

`Python` `faster-whisper` `CUDA` `WebSocket` `VS Code Extension` · 提供可安裝 VSIX、專有名詞熱更新、單元測試、依賴弱點檢查與 GitHub Actions

### [Unity AI Piano Composer（大學團隊專題）](https://github.com/steven65026502/unity-piano)

將可彈奏的 3D 鋼琴、音符事件資料、PyTorch Music Transformer 與本機 TCP 服務串成跨語言系統；Python 生成 piano-roll JSON 後，由 Unity 自動演奏。

`Unity` `C#` `Python` `PyTorch` `TCP Socket` `JSON` · 兩人團隊專題，個人主要負責資料前處理、模型訓練／生成、後期 Socket 與場景整合

### [國道車流 AI 分析與應用（競賽專案）](https://github.com/AI-CompetitionTeam/national-highway-traffic-management-competition)

為 2025 年國道智慧交通管理創意競賽整理 2024 年 TDCS 與國道五號沿線雨量資料；實作日期式下載、失敗重試、分批解壓縮、時間特徵與 K-means 探索性分群。全年實驗產生數百 GB 中間檔，公開 repository 只保留程式與少量彙整資料。

`Python` `Pandas` `scikit-learn` `Requests` `Open Data` · 公開 repository 保留原始提交紀錄，程式中的大型資料路徑與個資已整理

### [AgriNova 農業智慧決策工具（AI Junior Award 團隊提案）](projects/agrinova-ai-junior-award.md) · [提案影片（4:06）](https://drive.google.com/file/d/1P7MUwebsCQwi854lPac5OW1pL5O4XU7q/view?usp=sharing)

以農產品供需與極端天氣造成的決策落差為題，規劃整合氣象、產量與價格資料的決策介面，並用 NLP 整理新聞等非結構化資訊。團隊完成網站原型與 4 分鐘中英字幕提案影片。

`AI Product Design` `NLP` `Data Integration` `Market Demand Prediction` · 競賽概念與原型作品，未宣稱得獎或正式上線

### [Codex Agent Skills 可攜式技能包](https://github.com/steven65026502/codex-skills-shareable)

將 41 個 Agent Skills 整理為可公開分享的 Windows 安裝包，保留來源與授權，並移除個資與憑證。

`PowerShell` `Codex Agent Skills` · 具自動安裝、格式驗證、隱私掃描、第三方授權與完整使用文件

## 我重視的工程方法

- 先定義資料契約、邊界條件與失敗行為，再實作功能。
- 以測試、對帳、log 與可重跑流程留下可驗證證據。
- 文件同時說明如何使用、如何部署、已知限制與交接方式。
- AI 協作成果必須能讀懂、能修改、能測試，也能清楚說明取捨。

## 技術主軸

`Python` · `Pandas` · `SQL` · `PostgreSQL/PostGIS` · `FastAPI` · `QGIS/PyQGIS` · `Unity/C#` · `PyTorch` · `Git/GitHub Actions` · `HTML/CSS/JavaScript` · `Cloudflare Workers`

更多實作細節、限制與驗證方式，請從上方各專案 README 開始閱讀。
