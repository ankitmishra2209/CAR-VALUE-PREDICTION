# 🚗 CAR VALUE PREDICTION

Ye project purani (used) car ki selling price predict karta hai. 
Jaise car kitni purani hai, kitni chali hai, kaunsi company ki hai - us hisaab se price batata hai.

### 📂 Files
- `car_prediction.py` - Main Code
- `car_data.csv` - Dataset (301 Cars)

### 🛠️ Tech Stack
- Python, Pandas, Scikit-Learn, Matplotlib

### ✨ Kya Kiya Maine?
1. Naye Features Banaye: `Car_Age`, `Brand`, `Kms_per_Year`
2. 3 Models Compare Kiye: Linear Regression, Random Forest, HistGradientBoosting
3. Best Model: HistGradientBoosting

### 📊 Result
- **R2 Score: 0.96**
- **MAE: 0.45 Lakhs** (Matlab average sirf 45,000 ki galti)

### ▶️ Kaise Chalaye?
```bash
pip install pandas scikit-learn matplotlib
python car_prediction.py
