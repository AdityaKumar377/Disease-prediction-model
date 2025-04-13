# 🩺 Disease Prediction Model
This is a machine learning project that predicts diseases based on symptoms provided by the user. It uses multiple models to improve accuracy and returns a final prediction based on the majority vote.

## 💡 How It Works
- The user inputs symptoms as a comma-separated string (e.g., `Headache,Fatigue,Loss Of Appetite`).
- The system processes the symptoms and uses three ML models:
  - Random Forest
  - Naive Bayes
  - Support Vector Machine (SVM)
- Each model makes a prediction.
- The final result is based on the most common prediction among the three.

## 📦 Required Libraries
Make sure the following Python libraries are installed:
- numpy
- pandas
- scikit-learn

You can install them using:
```bash
pip install numpy pandas scikit-learn
```

## 🚀 How to Use
1. Open the script or notebook.
2. Run the code.
3. When prompted, enter symptoms like:
   ## 🧪 Example Inputs
- `Fever,Cough,Shortness Of Breath`
- `Joint Pain,Skin Rash,Fatigue`
- `Nausea,Vomiting,Abdominal Pain`
- `Blurred Vision,Increased Thirst,Frequent Urination`
4. The model will output predictions from each classifier and a final diagnosis.
