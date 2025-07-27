# Crop Prediction Using Machine Learning

This project uses machine learning models to predict the most suitable crop to grow based on soil characteristics. It includes models like **Random Forest**, **K-Nearest Neighbors**, and **Decision Tree**, with cross-validation and performance evaluation.

---

## Dataset

- Features include soil parameters like:
  - Nitrogen
  - Phosphorus
  - Potassium
  - Temperature
  - Humidity
  - pH
  - Rainfall
- The target variable is the **crop label** (encoded as numbers from 0 to 19).

---

## Tech Stack

- Python 
- Libraries:  
  - `pandas`, `numpy`, `matplotlib`, `seaborn`  
  - `scikit-learn` for ML algorithms and metrics  
- Jupyter Notebook 

---

## ⚙️ Models Used

- Random Forest Classifier (`Best Accuracy`)
- Decision Tree Classifier
- K-Nearest Neighbors

---

## 📈 Model Evaluation

- **Train-Test Split:** 80-20
- **Best Accuracy (Random Forest):**  
  - Accuracy: `98.24%`
- **Metrics Used:**
  - Accuracy Score
  - Classification Report
  - Confusion Matrix (visualized)

---

## 🧪 How to Run

```bash
git clone https://github.com/shubhangi115/Crop_Recomendation.git
cd your-repo-name
# Run the notebook or Python script
