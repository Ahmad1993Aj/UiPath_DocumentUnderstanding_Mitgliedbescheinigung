# UiPath Document Understanding Workflow: Membership Certificate Processing  
**Automated Extraction of Handwritten Data with AI and Human Validation**  

![UiPath-Document-Understanding](https://img.shields.io/badge/UiPath-Document_Understanding-important) 
![AI-Center](https://img.shields.io/badge/AI%20Center-ML_Model-blue) 
![GitHub](https://img.shields.io/badge/GitHub-Integrated-success)

---

## 📌 Overview  
This UiPath workflow automates the extraction of handwritten information from membership certificates using **Document Understanding** and a custom ML model trained in **UiPath AI Center**.
Extracted data is validated by humans, exported to Excel.

---

## ✨ Key Features  
- **AI/ML Model Training**: Custom model for handwritten text extraction via UiPath AI Center.  
- **Human-in-the-Loop Validation**: Manual correction of low-confidence extractions.  
- **Excel Export**: Structured output to Excel files.  
- **Orchestrator Integration**: Centralized process management (optional).  
- **Confidence Thresholds**: Auto-approve high-confidence data (e.g., ≥80%).  
- **GitHub Version Control**: Full project history and collaboration.

---

## 🛠️ Prerequisites  
1. **UiPath Studio 2022+** with installed packages:  
   - `UiPath.DocumentUnderstanding.ML`  
   - `UiPath.AI.MLServices`  
   - `UiPath.Excel.Activities`
   - `UiPath.IntelligentOCR.Activities`
   - `UiPath.DocumentUnderstanding.ML.Activities`
2. Access to **UiPath AI Center** (for model training).  
3. **Microsoft Excel** for data export.  
4. (Optional) UiPath Orchestrator for cloud orchestration.  
5. GitHub account for repository management.
6. -------------> Please ADD the API-Key

---
