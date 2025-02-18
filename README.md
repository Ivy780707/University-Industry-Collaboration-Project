# University-Industry Collaboration Project

## Requirements
This project is a collaboration between **NCKU Data Analytics Club** and **KDAN Mobile Taiwan**, aiming to enhance **membership management and marketing strategies** through data analysis and machine learning.  

### Technologies Used:
- **Python** (Data analysis and machine learning)
- **Jupyter Notebook** (Data processing and visualization)
- **Random Forest** (Machine learning model)
- **NAPL Segmentation Model** (New, Active, Potential, Lost, SealedReady)

> **Note**: Due to corporate data confidentiality, this project does not include the original dataset.

### Environment Setup:
Ensure Python is installed, then run:
```bash
pip install -r requirements.txt
```
### Usage:
- **Launch Jupyter Notebook**
```bash
jupyter notebook
```
- **Train the Machine Learning Model**
```bash
python src/train_model.py
``` 
---

## Useful Resources
### Analysis Methods & Techniques
- **Data Analysis**: Membership statistics, purchasing behavior analysis, and marketing impact evaluation
- **NAPL Model**: Customer segmentation and loyalty analysis
- **Machine Learning**: Random Forest model, feature engineering, model evaluation

### Key Findings:
- **Enhancing customer engagement for high-value members**
- **Personalized marketing strategies for specific customer segments**
- **Predicting customer churn risk and implementing preventive strategies**

---

## Project Structure
```plaintext
📂 Project/
│── 📂 notebooks/            # Jupyter Notebook for data analysis
    │── 📄 data.ipynb        #EDA process
    │── 📄 mock_order.csv    #mock data of orders
    │── 📄 mock_member.csv   #mock data of members
    │── 📄 mock_behavior_202207.csv  ##mock data of customer behaviors in 2022/07
│── 📂 src/                  # Python scripts for model training
│── 📄 requirements.txt      # Python dependencies
│── 📄 README.md             # This document
```





