# Indonesia Property Price Prediction

A machine learning project that predicts property prices in East Java, Indonesia by comparing three different algorithms: Linear Regression, Random Forest, and Decision Tree.

## Project Overview

This project demonstrates the complete machine learning workflow from data preparation to model evaluation. As a full stack web developer expanding into AI/ML, I created this project to connect with my existing work in property technology ([Next Level Properti](https://nextlevelproperti.com)).

## Dataset

The project uses a **synthetic dataset** of 1,000 properties across 5 East Java cities (Surabaya, Sidoarjo, Gresik, Malang, Batu) with realistic patterns based on actual market conditions. Using synthetic data allowed me to focus on learning ML concepts while avoiding data privacy concerns.

### Features
- **Location:** City
- **Property Type:** Rumah (House), Apartemen (Apartment), Ruko (Shop House), Villa
- **Physical:** Land area, building area, bedrooms, bathrooms, carport
- **Legal:** Certification type (SHM, SHGB, HGU)
- **Target:** Price in million IDR

## Models & Results

| Model | Accuracy (R²) | MAE | RMSE |
|-------|---------------|-----|------|
| **Random Forest** | **93.48%** | 276M IDR | 410M IDR |
| Decision Tree | 88.68% | 372M IDR | 541M IDR |
| Linear Regression | 85.72% | 444M IDR | 607M IDR |

**Winner:** Random Forest with 93.48% accuracy

## Key Insights

- Building area is the most important price factor (85% importance)
- Location significantly impacts price (Surabaya properties are most expensive)
- Random Forest outperforms simpler models for this prediction task

## Technologies Used

- **Python** - Programming language
- **Google Colab** - Development environment
- **Pandas & NumPy** - Data manipulation
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning algorithms

## Getting Started

### View the Notebook
Open `Indonesia_Property_Price_Prediction_Aucky.ipynb` in Google Colab or Jupyter Notebook.

### Run Locally
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Then open the notebook file in Jupyter or upload to Google Colab.

## What I Learned

- Data preparation and encoding categorical variables
- Exploratory data analysis and visualization
- Training and comparing multiple ML algorithms
- Model evaluation metrics (MAE, RMSE, R² Score)
- Making practical predictions with trained models

## Future Improvements

- Integrate real Indonesia property data from public sources
- Add more features (proximity to facilities, year built, etc.)
- Deploy as a web API using Flask/FastAPI
- Create a simple web interface for price predictions

## Portfolio Context

This is my second portfolio project for the **Apple Developer Institute for AI/ML @ UC Surabaya** admission (Cohort 2026). It demonstrates my progression into machine learning while building on my full stack development background.

**Other Portfolio Projects:**
- [LeafScan](https://github.com/auckyrh/LeafScan-iOS) - iOS plant disease detection app using Core ML
- [Next Level Properti](https://github.com/swrhythm/wpi-project)  - Property listing web application (Laravel) - [https://nextlevelproperti.com] 

## License

MIT License - feel free to use this project for learning purposes.

## Contact

- **GitHub:** [https://github.com/auckyrh]
- **LinkedIn:** [https://www.linkedin.com/in/aucky/]
