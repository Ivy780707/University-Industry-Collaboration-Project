# University-Industry-Collaboration-Project

## 1️⃣ 專案簡介 (Project Overview)
本專案由 **[國立成功大學資料分析社]** 與 **[KDAN Mobile Taiwan]** 合作，旨在透過 **數據分析與機器學習** 優化會員管理與行銷策略。  
我們運用 **NAPL 分群模型** (New, Active, Potential, Lost, SealedReady)，並透過 **機器學習預測** 會員行為，幫助企業制定個性化行銷方案。  

### 📌 主要研究方向：
- 會員行為模式分析
- 顧客分群與忠誠度分析 (NAPL)
- 機器學習模型預測會員類型
- **個性化行銷策略建議**

> 🔒 **資料集屬於企業機密，本專案不包含原始數據。**

---

## 2️⃣ 方法與技術 (Methodology & Techniques)

### 🔍 數據分析
- **會員屬性統計** (性別、年齡、會員等級)
- **購物行為分析** (熱門時段、購買頻率、折扣反應)
- **行銷推播效果評估** (SMS、Email、LINE 影響力)

### 🔥 NAPL 顧客分群
- **New (新會員)**: 首次購買後如何引導再消費？
- **Active (活躍會員)**: 如何維持高價值客群？
- **Potential (潛在高價值會員)**: 如何提升轉換率？
- **Lost (流失會員)**: 透過再行銷降低流失？
- **SealedReady (忠誠會員)**: 如何進一步增值？

### 🤖 機器學習預測
- **模型選擇**: 隨機森林 (Random Forest)
- **特徵工程**:
  - 訂單行為 (`total_orders`, `shopping_cycle`)
  - 會員互動 (`is_sms`, `is_email`, `is_line`)
- **評估指標**:
  - 精確率 (Precision)
  - 召回率 (Recall)
  - F1-score

---

## 3️⃣ 使用方式 (How to Use)
🔒 **此專案不包含原始數據，但提供分析流程與模型訓練代碼。**  
可下載專案並運行 `notebooks/` 內的 Jupyter Notebook 進行數據分析。

### 🚀 安裝與執行
1. **安裝必要套件**
    ```bash
    pip install -r requirements.txt
2. **開啟 Jupyter Notebook** 
    ```bash
    jupyter notebook
3. **進行模型訓練**
    ```bash
    python src/train_model.py

---

## 4️⃣ 專案架構 (Project Structure)
📂 KDAN_Project/
│── 📂 notebooks/            # 數據分析 Jupyter Notebook (範例數據)
│── 📂 src/                  # Python 主要程式碼
│── 📄 requirements.txt      # 需要安裝的 Python 套件
│── 📄 README.md             # 本文件


---

## 5️⃣ 研究成果 (Findings & Insights)
🚧 **由於企業機密限制，本專案僅提供方法論，不展示分析結果與數據。**  
然而，我們的研究成果可以應用於：
- **提升高價值會員的消費黏著度**
- **針對特定客群提供個性化行銷**
- **預測會員流失風險，提前制定策略**

---

## 6️⃣ 參考資料 (References)
- **顧客行為分析理論**
- **機器學習應用於市場行銷**
- **NAPL 模型與會員分群方法**





