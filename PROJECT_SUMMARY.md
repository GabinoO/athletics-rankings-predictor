# Athletics 1500m Ranking Predictor - Project Summary

## 🎯 Project Overview
A machine learning system that predicts top 15 rankings for men's 1500-meter track events using web-scraped data from World Athletics.

## 📊 Key Results
- **Accuracy**: 73.33% on exact rank predictions
- **Precision**: 73.33% on top 15 athletes (2025)
- **Data Coverage**: 6 years (2020-2025) of men's 1500m rankings
- **Model**: Random Forest Classifier with feature engineering

## 🛠️ Technical Implementation
1. **Web Scraping**: Automated data collection from World Athletics
2. **Data Processing**: Feature engineering with rolling averages
3. **Machine Learning**: Random Forest for ranking prediction
4. **Evaluation**: Cross-year validation on 2025 data

## 🏆 Notable Predictions
- **Jakob INGEBRIGTSEN**: Predicted 1st, Actual 1st ✅
- **Hobbs KESSLER**: Predicted 3rd, Actual 3rd ✅
- **Azeddine HABZ**: Predicted 4th, Actual 4th ✅

## 💼 Resume-Ready Skills Demonstrated
- **Data Science**: End-to-end ML pipeline
- **Web Scraping**: Automated data collection
- **Feature Engineering**: Rolling averages, categorical encoding
- **Machine Learning**: Random Forest, model evaluation
- **Data Processing**: pandas, scikit-learn
- **Project Management**: Clean code structure, documentation

## 📁 Repository Structure
```
├── Webscraper.ipynb          # Data collection
├── Predictor.ipynb           # ML model
├── Athletics_rankings.csv    # Dataset
├── requirements.txt          # Dependencies
├── README.md                # Documentation
└── LICENSE                  # MIT License
```

## 🚀 Quick Start
```bash
git clone <repository-url>
pip install -r requirements.txt
jupyter notebook
```

---
*Perfect for showcasing data science skills to recruiters!* 