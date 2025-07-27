# Stock Analyzer

The **Stock Analyzer** project is a complete stock market analysis tool utilizing ML models. It allows users to input stock symbols, select date ranges, view historical stock trends, and see future stock price predictions via interactive charts.

<div align = "center"
<img alt="Stars" src="https://img.shields.io/github/stars/SrigadaAkshayKumar/stock?style=flat&logo=github"/>
<img alt="Forks" src="https://img.shields.io/github/forks/SrigadaAkshayKumar/stock?style=flat&logo=github"/>
<img alt="Issues" src="https://img.shields.io/github/issues/SrigadaAkshayKumar/stock?style=flat&logo=github"/>
<img alt="Open Pull Requests" src="https://img.shields.io/github/issues-pr/SrigadaAkshayKumar/stock?style=flat&logo=github"/>
<img alt="Close Pull Requests" src="https://img.shields.io/github/issues-pr-closed/SrigadaAkshayKumar/stock?style=flat&color=green&logo=github"/>
</div>
## Live Demo

[View Deployed App on Render](https://aistockanalyzer.onrender.com)

---

## Overview

### Home Page

![Home Page](Images/home.png)

### Stock Analysis View

![Stock Analysis](Images/main.png)

### Stock Predictions

## ![Stock prediction](Images/prediction.png)

## Technologies Used

- **React:** User Interface
- **Plotly.js:** Interactive visualizations
- **Axios:** API calls
- **Flask:** Backend Framework
- **yfinance:** Stock data extraction
- **Pandas:** Data manipulation
- **Scikit-learn:** to load and use the model

---

## Directory Structure

```
Directory structure:
└── srigadaakshaykumar-stock/
    ├── README.md
    ├── SETUP.md
    ├── CONTRIBUTION.md
    ├── package.json
    ├── static.json
    ├── backend/
    │   ├── app.py
    │   ├── requirements.txt
    │   ├── stock-prediction.ipynb
    │   └── tf.keras
    ├── public/
    │   ├── index.html
    │   ├── manifest.json
    │   └── robots.txt
    └── src/
        ├── App.css
        ├── App.js
        ├── App.test.js
        ├── index.css
        ├── index.js
        ├── reportWebVitals.js
        ├── setupTests.js
        └── components/
            ├── AuthContext.js
            ├── firebase.js
            ├── Footer.jsx
            ├── Header.jsx
            ├── Login.js
            ├── Prediction.jsx
            ├── Signup.js
            ├── Stockdata.jsx
            ├── StockList.jsx
            └── data/
                └── stockData.json
```

---

## API Endpoints

| **Endpoint**                          | **Method** | **Description**                                  |
|--------------------------------------|------------|--------------------------------------------------|
| `/api/stocks/<ticker>`               | GET        | Fetch historical stock data                      |
| `/api/predict/<ticker>`              | GET        | Predict future stock prices                      |
| `/api/export/history?ticker=...`     | GET        | Download historical data as CSV or Excel         |
| `/api/export/predictions?ticker=...` | GET        | Download prediction results as CSV or Excel      |

---

## Data Pipeline Architecture

![Home Page](Images/dataline.png)

---

## Project Status

**Stock Analyzer** is currently in the **development stage** and hosted on a free hosting service for testing purposes.

## Future Enhancements

We have a clear roadmap for improvements:

- Allow more API calls per day
- Reduce response time for end users
- Add Internatinal stock exchanges
- Enhance the user interface for better experience
- Improve machine learning model accuracy
- Provide more insightful and interactive visualizations
- Migrate deployment from Render to Google Cloud Platform (GCP)

## Contributions

We welcome all forms of open-source contributions — whether it's a:

- Bug fix
- New feature
- Enhancement or optimization

Please make sure to:

- Review our [Contribution Guidelines](./CONTRIBUTION.md)
- Follow the [Setup Instructions](./SETUP.md) to run the project locally
- Join the [Discord](https://discord.gg/ypQSaPbsDv)

## License

This project is licensed under the [MIT License](LICENSE).  
You’re free to use, modify, and share this software under the license terms.
