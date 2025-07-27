# Crop Prediction Using Machine Learning

This project applies machine learning algorithms to predict the best crop choice based on soil characteristics. The employed models are **Random Forest**, **K-Nearest Neighbors**, and **Decision Tree**, and cross-validation and performance evaluation.

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
- Target variable is the **crop label** (numerically encoded between 0 and 19).

---

## Tech Stack

- Python 
- Libraries:  
  - `pandas`, `numpy`, `matplotlib`, `seaborn`  
  - `scikit-learn` for ML algorithms and metrics  
- Jupyter Notebook 

---

## Models Used

- Random Forest Classifier (Highest Accuracy)
- Decision Tree Classifier
- K-Nearest Neighbors

---

## Model Evaluation

- - **Train-Test Split:** 80-20
- **Highest Accuracy (Random Forest):**
- Accuracy: `98.24%`
- **Metrics Used:**
  - Accuracy Score
  - Classification Report
  - Confusion Matrix (visualized)

---

## How to Run

```bash
git clone https://github.com/shubhangi115/Crop_Recomendation.git
cd Crop_Recomendation
# Run the notebook or Python script
