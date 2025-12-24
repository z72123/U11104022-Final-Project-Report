# 114-1 地球物理通論 期末專題報告 (Geophysics Final Project)

**探索地球的脈動：跨越地表與代碼的邊界**

| **課程資訊** | **作者資訊** |
| :--- | :--- |
| **課程名稱**：地球物理通論 (114學年度第1學期) | **學生**：張以蓁 (U11104022) |
| **指導教授**：陳達毅 教授 | **系級**：臺北市立大學 史地學系四年級 |

---

## 🔗 專案成果展示 (Deployment)

* **🌐 互動式成果網頁 (GitHub Pages)**: [點擊進入線上展覽](https://z72123.github.io/U11104022-Final-Project-Report/)
* **🤖 AI 知識庫助手 (Dify)**: [試用 AI Bot](https://udify.app/workflow/lgcgpFF9BWLuE9fL)
* **🌍 重力異常互動模擬 (HuggingFace)**: [操作 Gradio App](https://huggingface.co/spaces/Z72123/freeair-gtavity)

---

## 📖 專案簡介 (Introduction)

本專案為「地球物理通論」課程的期末成果展。作為一名史地系學生，我嘗試將**人文的時空觀點**與**地球物理的探勘技術**結合。

這不僅是一份作業合輯，更是一段從「閱讀文獻」轉向「解讀數據」的學習旅程。網站採用**深色科技風格 (Dark Mode Tech Theme)** 設計，象徵潛入深邃的地底世界，利用 Python、AI 與視覺化工具，重新認識我們腳下的地球。

---

## 🗺️ 學習旅程地圖 (Learning Roadmap)

本學期的探索路徑分為四個階段，循序漸進地構建跨領域能力：

* **Stage 1: 建構數位基礎**
    * 熟悉 GitHub Ecosystem、Codespaces 雲端環境與 ObsPy 套件架設。
* **Stage 2: 驗證物理理論**
    * 從司乃耳定律推導折射公式，並進行校園實地敲擊震測，驗證地下速度構造。
* **Stage 3: 探索地球場**
    * 深入重力異常修正、古地磁極漂移 (APWP) 與大地電磁法 (MT) 的地質意義。
* **Stage 4: 視覺化與 AI 賦能**
    * 利用 PyGMT 繪製高解析度地質圖，並整合 RAG 技術建立個人 AI 助手。

---

## 📚 核心內容架構 (Content Highlights)

網頁內容依據知識邏輯劃分為以下區塊：

### 1. ⚛️ 地球物理核心知識 (Core Knowledge)
以「研究員」視角解析四大核心主題，結合課堂理論與實作報告：
* **震測波形處理 (Seismic Processing)**：利用 ObsPy 進行濾波與去均值 (HW3)。
* **折射震測與解釋 (Refraction Seismology)**：推導 Crossover Distance 並分析野外數據 (HW4, HW5)。
* **位場：重力與古地磁 (Potential Fields)**：探討重力異常修正與板塊漂移證據 (HW7, HW8)。
* **大地電磁與地熱 (MT & Geothermal)**：介紹 MT 在探測低電阻率地熱儲集層的應用。

### 2. 🛠️ 數位工具與 AI (Digital Toolkit)
展示建立現代化研究工作流的工具鏈：
* **HuggingFace & Gradio**：部署互動式 Web App。
* **Google Blogger**：建立學習歷程檔案 (Portfolio)。
* **GitHub Codespaces**：雲端 Python 開發環境。
* **Dify AI Agent (HW9)**：建立專屬的地球物理 RAG 知識庫問答機器人。

### 3. 🗺️ PyGMT 視覺化專題 (Visualization)
* **入門教學 (HW11)**：製作 PyGMT 基礎教學網站，分享學習筆記。
* **進階應用 (HW10)**：撰寫 Colab 程式碼，繪製疊合地形、火山、地震與板塊邊界的綜合地質圖。

### 4. 🎤 大師演講摘要 (Masters' Insights)
汲取領域專家的前沿觀點：
* **甘禮有博士**：地震層析成像 (Seismic Tomography)。
* **黃有志博士**：火山觀測與無人機應用。
* **廖勿渝博士**：深度學習 (Deep Learning) 在地震監測的應用。

---

## 💻 網站技術 (Tech Stack)

本靜態網頁使用以下技術構建，強調互動性與響應式設計：

* **Frontend**: HTML5, CSS3, JavaScript
* **Framework**: [Bootstrap 5](https://getbootstrap.com/) (Dark Mode enabled)
* **Icons**: [FontAwesome 6](https://fontawesome.com/)
* **Fonts**: 'Noto Sans TC' (正文), 'JetBrains Mono' (程式碼風格)
* **Hosting**: GitHub Pages

---

## 📂 檔案結構 (File Structure)

```text
.
├── index.html          # 網站主程式 (Entry Point)
├── README.md           # 專案說明文件
└── assets/             # 資源資料夾
    ├── 作業3說明.pdf
    ├── 作業4-1.jpg
    ├── 作業4-2.jpg
    ├── 作業6演講心得報告.pdf
    ├── 作業12演講心得報告.pdf
    ├── 作業13演講心得報告.pdf
    ├── 第九組震測實驗報告.pdf
    ├── 地熱探勘上課資料.pdf
    └── pygmt_preview.jpg  # PyGMT 預覽圖