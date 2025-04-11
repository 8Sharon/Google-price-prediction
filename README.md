# 📈 Google Stock Price Prediction
![Stock Price Chart ](https://res.cloudinary.com/jerrick/image/upload/d_642250b563292b35f27461a7.png,f_jpg,fl_progressive,q_auto,w_1024/zr81hdsyfwjkgqcfsbbm.jpg)

 # Disclaimer ⚠️
All datasets, information, and reports within this repository are fictional and created solely for illustrative purposes to showcase advanced predictive machine learning techniques. They do not include any real proprietary, confidential, or sensitive information related to any company, organization, or individual. 
---


## 🗂️ Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Source](#source)
- [Data Cleaning](#data-cleaning)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [Contact](#contact)

---

## 📘 Introduction

This project aims to predict the stock prices of Google (GOOGL) using advanced machine learning models. The primary objective is to generate accurate and timely predictions that could assist in making better-informed investment decisions.

---

## 📊 Dataset

The dataset used for this project consists of historical stock prices for Google (GOOGL). It includes the following features:

| Feature      | Description                                      |
|--------------|--------------------------------------------------|
| Date         | The trading date                                 |
| Open Price   | Stock price at the market opening                |
| High Price   | Highest stock price during the trading day       |
| Low Price    | Lowest stock price during the trading day        |
| Close Price  | Stock price at the market closing                |
| Volume       | Number of shares traded during the day           |

## Source
The data can be sourced from reliable financial APIs or providers such as [Yahoo Finance](https://finance.yahoo.com/).

---

## 🧹 Data Cleaning

To ensure the quality and reliability of the model, the dataset underwent preprocessing which included:

- Removal of duplicate records
- Handling of missing values (imputation/filling)
- Conversion of dates to appropriate datetime formats
- Scaling of feature values for neural network training

---

## 🧠 Model Training

The primary model used in this project is a **Long Short-Term Memory (LSTM)** network due to its strong capability in learning temporal dependencies in time series data.

### Key Features:
- Sequence modeling using historical prices
- Tuned hyperparameters for better convergence
- Train/Test split with validation

---

## 📈 Evaluation

The model’s predictions were evaluated using the following performance metrics:

| Metric           | Description                                        |
|------------------|----------------------------------------------------|
| MSE (Mean Squared Error)       | Measures average squared difference between predicted and actual prices |
| RMSE (Root Mean Squared Error) | Square root of MSE; more interpretable due to units |
| R² Score        | Measures how well predictions approximate actual values |

---

## 📊 Results

The plot below shows the comparison between the actual and predicted Google stock prices:

![Google price Prediction Plot](google_price_prediction_plot.png)

The LSTM model was able to closely track the general trend of Google's stock price movements, indicating strong predictive capabilities.

---

# 🤝 Contributing

Contributions are welcome! If you'd like to help improve this project, please follow the steps below:

---

### 🧩 How to Contribute

1. **Fork** the repository to your GitHub account.

2. **Clone** your forked repo to your local machine:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name
3. **create new branch** for your feature or fix:
   ```bash
   git checkout -b feature-branch
4. **make changes** commit them:
   ```bash
   git commit -m "Add feature"
5. **push your changes** to your forked repository:
  git push origin feature-branch

## 📬 Contact

For questions, suggestions, or feedback, feel free to reach out:

- 📧 **Email**: [njerisharon611@gmail.com](njerisharon611@gmail.com)  
- 🧑‍💻 **GitHub**: [8Sharon](https://github.com/8Sharon)  
- 🐛 **Project Issues**: Use the [GitHub Issues](https://github.com/8Sharon/Google-price-prediction/issues) tab to report bugs or request features.



