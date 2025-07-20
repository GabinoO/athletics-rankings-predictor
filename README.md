# Athletics 1500m Ranking Predictor

A machine learning project that predicts top 15 rankings for men's 1500-meter track events using web-scraped data from World Athletics.

## 🏃‍♂️ Project Overview

This project demonstrates end-to-end data science workflow:
- **Web Scraping**: Automated data collection from World Athletics website
- **Data Processing**: Feature engineering and data cleaning
- **Machine Learning**: Random Forest model for ranking prediction
- **Performance Analysis**: Model evaluation and insights

## 📊 Results

- **Precision**: 73.33% on top 15 athletes (2025 predictions)
- **Accuracy**: 73.33% (exact rank predictions)
- **Data Coverage**: 6 years (2020-2025) of men's 1500m rankings
- **Athletes Predicted**: Top 15 performers in 2025

## 🛠️ Technical Stack

- **Python 3.11**
- **Data Processing**: pandas, numpy
- **Web Scraping**: requests, beautifulsoup4
- **Machine Learning**: scikit-learn (Random Forest)
- **Development**: Jupyter Notebooks

## 📁 Project Structure

```
├── Webscraper.ipynb          # Data collection from World Athletics
├── Predictor.ipynb           # ML model training and evaluation
├── Athletics_rankings.csv    # Scraped dataset (2020-2025)
├── requirements.txt          # Python dependencies
├── README.md                # This file
└── .gitignore               # Git ignore rules
```

## 🚀 Getting Started

### Prerequisites
- Python 3.11+
- pip or conda

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/athletics-ranking-predictor.git
   cd athletics-ranking-predictor
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the notebooks**
   ```bash
   jupyter notebook
   ```

### Usage

1. **Data Collection** (Optional - data already included)
   - Open `Webscraper.ipynb`
   - Run all cells to scrape fresh data from World Athletics

2. **Model Training & Evaluation**
   - Open `Predictor.ipynb`
   - Run all cells to train the model and view results

## 📈 Model Details

### Features Used
- **Athlete Information**: Athlete code, nationality
- **Performance Metrics**: Current rank, previous year rank
- **Trend Analysis**: Rolling averages of performance and ranking history
- **Competition Data**: Venue codes, competition dates

### Model Configuration
- **Algorithm**: Random Forest Classifier
- **Parameters**: 50 estimators, min_samples_split=7
- **Target**: Predict rank positions (1-15)
- **Training Data**: 2020-2024 rankings
- **Test Data**: 2025 rankings

### Performance Metrics
```
Precision Score: 73.33%
Accuracy: 73.33%
```

## 🎯 Key Insights

### Top Predictions (2025)
1. **Jakob INGEBRIGTSEN** - Predicted: 1st, Actual: 1st ✅
2. **Yared NUGUSE** - Predicted: 1st, Actual: 2nd
3. **Hobbs KESSLER** - Predicted: 3rd, Actual: 3rd ✅
4. **Azeddine HABZ** - Predicted: 4th, Actual: 4th ✅

### Model Strengths
- Excellent prediction of top performers
- Captures athlete consistency patterns
- Handles international competition data effectively

## 🔧 Technical Features

### Data Processing
- **Time Conversion**: MM:SS.ms format to total seconds
- **Feature Engineering**: Rolling averages for trend analysis
- **Categorical Encoding**: Athlete, venue, and nationality codes
- **Missing Data Handling**: Graceful handling of incomplete records

### Web Scraping
- **Automated Collection**: 6 years of historical data
- **Data Cleaning**: Standardized format across years
- **Error Handling**: Robust scraping with verification

## 📊 Data Sources

- **Primary Source**: [World Athletics Rankings](https://worldathletics.org/records/toplists/middlelong/1500-metres/all/men/senior)
- **Event**: Men's 1500m (senior category)
- **Time Period**: 2020-2025
- **Data Points**: ~600 athlete performances

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

**Gabino Ocotl**
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/gabino-ocotl-479a532b5/)

## 🙏 Acknowledgments

- World Athletics for providing the ranking data
- The athletics community for inspiration
- Open source contributors to the libraries used

---

**Note**: This project is for educational and portfolio purposes. Predictions are based on historical data and should not be used for betting or official rankings. 
