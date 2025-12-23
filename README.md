# 114-1 地球物理通論 期末專題報告 (Final Project)

**學生：** 史地四 U11104022 張以蓁  
**指導教授：** 陳達毅 教授

---

## 🔗 成果展示連結 (Deployment)
* **互動式成果網頁 (GitHub Pages):** [https://z72123.github.io/U11104022-Final-Project-Report/](https://z72123.github.io/U11104022-Final-Project-Report/)
* **AI 互動助手 (Dify):** [https://udify.app/workflow/lgcgpFF9BWLuE9fL](https://udify.app/workflow/lgcgpFF9BWLuE9fL)
* **重力異常分析 App (Hugging Face):** [https://huggingface.co/spaces/Z72123/freeair-gtavity](https://huggingface.co/spaces/Z72123/freeair-gtavity)

---

## 📚 專案架構與內容整合 (Content Integration)

本專案旨在透過互動式網頁，完整呈現本學期在地球物理領域的學習歷程。作為史地系學生，我嘗試將地理空間的思維與地球物理的數據分析結合，內容涵蓋四大面向：

### 1. 🛠️ 數位工具基礎 (Digital Infrastructure)
* **目的：** 建立雲端開發與數據獲取能力。
* **成果：** * 熟練使用 **GitHub Codespaces** 進行 Python 開發。
  * 利用 **ObsPy** 串接 IRIS 資料庫，獲取並處理地震波形數據 (HW3)。

### 2. 📝 理論與實地測勘 (Theory & Fieldwork)
* **目的：** 驗證地球物理理論。
* **成果：**
  * **公式推導：** 詳解折射震測中的 Crossover Distance 與走時公式 (HW4)。
  * **校園實驗：** 實地操作 24 通道震測儀，成功推算出校園地下第一層波速 (400 m/s) 與厚度 (4.21 m) (HW5)。

### 3. 🗺️ 資料視覺化 (Data Visualization)
* **目的：** 將抽象數據轉化為直觀的地質資訊。
* **成果：**
  * 使用 **PyGMT** 繪製包含地形、火山與地震分佈的板塊邊界圖 (HW10)。
  * 建立 PyGMT 教學網頁，分享繪圖程式碼與經驗 (HW11)。

### 4. 🤖 AI 與深度學習應用 (AI Integration)
* **目的：** 探索新科技在地球科學的應用。
* **成果：**
  * **RAG 應用：** 建立 Dify 知識庫助手，輔助地球物理概念查詢 (HW9)。
  * **互動展示：** 部署 Gradio App，動態展示重力異常修正原理 (HW8)。

---

## 📂 檔案目錄說明 (Structure)

```text
.
├── index.html          # 網站主程式 (Entry Point)
├── README.md           # 專案說明與部署連結 (本文件)
└── assets/             # 靜態資源 (報告與圖片)
    ├── 作業3說明.pdf
    ├── 作業4-1.jpg
    ├── 作業4-2.jpg
    ├── 作業6演講心得報告.pdf
    ├── 作業12演講心得報告.pdf
    ├── 作業13演講心得報告.pdf
    └── 第九組震測實驗報告.pdf