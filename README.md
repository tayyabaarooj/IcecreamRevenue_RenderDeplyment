# 🍦 Ice Cream Revenue Prediction | Render Deployment Demo  

This repository demonstrates how to deploy a simple **Linear Regression model** on **Render**. The model predicts ice cream sales revenue based on temperature using a dataset from Kaggle.  

## 📌 Features  
- **Linear Regression Model** for revenue prediction  
- **Flask API** for model deployment  
- **Render Deployment Guide**  

## 📊 Dataset  
The dataset contains historical ice cream sales data with temperature as the key predictor. You can find the dataset on Kaggle: **https://www.kaggle.com/datasets/vinicius150987/ice-cream-revenue**  

## 🚀 Setup & Usage  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/ice-cream-revenue-prediction.git
cd ice-cream-revenue-prediction
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run Locally  
```bash
python app.py
```
The API will be available at `http://localhost:5000`.

### 4️⃣ Deploy on Render  
Follow these steps to deploy the model on **Render**:
1. Create a **new web service** on [Render](https://render.com).
2. Connect your GitHub repository.
3. Set the **Build Command** to:  
   ```bash
   pip install -r requirements.txt
   ```
4. Set the **Start Command** to:  
   ```bash
   python app.py
   ```
5. Deploy and get the live API URL! 🎉  

## 🛠 Tech Stack  
- **Python**  
- **Flask** (for API)  
- **Scikit-Learn** (for model training)  
- **Render** (for deployment)  

## 📬 Contact  
For any queries or suggestions, feel free to reach out or open an issue. 🚀  
