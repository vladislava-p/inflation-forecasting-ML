# Inflation Forecasting with ML & NLP

This project predicts inflation rates in Russia using macroeconomic data combined with topic modeling of over 96,000 news articles.

## Goal
To develop a hybrid model that integrates structured economic indicators and unstructured news text to forecast inflation using ML techniques.

## Tools & Technologies
- **Python**: pandas, scikit-learn, gensim, nltk, matplotlib, seaborn
- **ML Models**: Random Forest, LASSO, ElasticNet
- **NLP**: LDA topic modeling (Gensim)
- **Time Series**: Statsmodels, smoothing
- **EDA**: correlation plots, visual analysis

## Key Steps
- Collected macroeconomic indicators (inflation, GDP, M2, etc.)
- Scraped and cleaned economic news data
- Applied LDA to extract latent topics
- Built predictive models combining both types of data
- Evaluated performance using DM-test, RMSE and cross-validation

## Project Structure
- `inflation_model.ipynb` — full pipeline: data prep, modeling, evaluation
- `data/` — sample datasets (mockup or real)
- `results/` — plots, metrics, exported model

## Results
- Best model: **ElasticNet** with macro + LDA features  
- RMSE on test set: **0.37**

## Contact
If you have questions or want to collaborate, feel free to reach out:
- pileckavladislava@gmail.com
- Telegram: @pillecka
