# 🏏 IPL Win Predictor

The **IPL Win Predictor** is a Machine Learning project that predicts the winning probability of teams in an Indian Premier League (IPL) match.

---

## 🔹 Features
- Uses historical **IPL match and ball-by-ball data** (Kaggle/ESPN CricInfo).  
- Feature engineering on **runs, balls, wickets, CRR, RRR**.  
- Models: **Logistic Regression, Random Forest, XGBoost**.  
- Works in **real time** – enter match details and get probabilities.  
- Interactive **web app** using **Streamlit / Flask**.  

---

## 🔹 Tech Stack
- **Python**  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Models:** Logistic Regression, Random Forest, XGBoost  
- **Deployment:** Streamlit / Flask  
- **Dataset:** IPL ball-by-ball and match-level data (Kaggle/ESPN CricInfo)  

---

## 🔹 Example
If a team needs **40 runs from 24 balls with 6 wickets left**,  
the model will predict winning probabilities for **both batting and bowling teams**.  

---

## 🔹 Applications
- Cricket fans can estimate match outcomes in real time.  
- Analysts can explore match dynamics.  
- Demonstrates a full **end-to-end ML workflow** (Data → Model → Deployment).  

---

## 🚀 How to Run
1. Clone the repository.  
2. Install requirements:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run data preprocessing & model training.  
4. Launch the app:  
   
   streamlit run app.py
   
   or  
   
   python app.py
   
