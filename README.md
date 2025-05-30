# federated-medical-diagnosis
This project simulates a federated learning environment where two medical datasets — breast cancer and cardiovascular — are used to mimic client-side training. Each dataset is treated as a separate institution, and logistic regression or deep learning models are trained independently. Instead of using a real FL server, this setup manually aggregates performance metrics to emulate global model behavior.

---

## 🎯 Objectives

- Simulate federated learning behavior for healthcare diagnosis.
- Preserve data privacy by avoiding centralized data merging.
- Evaluate model performance per client and in aggregate.

---

## 🧪 Datasets Used

- **Breast Cancer**: Classification based on tumor features.
- **Cardiovascular Disease**: Prediction using clinical health indicators.

---

## ⚙️ Technologies

- Python 3
- TensorFlow / Scikit-learn
- Pandas, NumPy
- Google Colab

---

## 📁 File Structure
federated-medical-diagnosis/
├── pbl_final.ipynb # Main notebook
├── breast-cancer.csv # Dataset 1
├── cardio_train.csv # Dataset 2

---

## 📈 Results

| Dataset        | Accuracy  |
|----------------|-----------|
| Breast Cancer  | ~96%      |
| Cardiovascular | ~72%      |

---

## 🔐 Privacy Perspective

Although no real federated server is used, the project structure ensures:
- No raw data sharing
- Simulated client separation
- Model evaluation under a federated paradigm

---

## 📚 Future Scope

- Implement true FL using Flower or PySyft
- Integrate Differential Privacy or Homomorphic Encryption
- Expand to multi-task and real-time clinical environments

---



