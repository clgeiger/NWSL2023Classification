# Predicting NWSL Match Outcomes  

This repository contains a machine learning project focused on predicting match outcomes (win, loss, tie) for the 2023 National Women’s Soccer League (NWSL) season. Using statistical analysis and machine learning models, this project explores game statistics to predict match results.  

---

## Project Overview  

- **Data Source**: Manually entered first-half game statistics for all 2023 NWSL games.  
- **Preprocessing**: Addressed missing data, class imbalance, and feature selection.  
- **Feature Selection**: Techniques such as Mutual Information Scores, F-statistics, and Random Forest Importance were used to identify the most predictive features.  
- **Models Used**: Logistic Regression and Decision Tree models were developed and optimized for two versions:  
  1. **Win/Loss/Tie Classification**: Predicts all three possible outcomes for a game.  
  2. **Win/Not Win Classification**: Combines losses and ties into a single category, focusing on whether a team wins or does not win.  

- **Neural Network Models**: Initially explored, but ultimately excluded due to significant issues with overfitting and an inability to predict ties accurately.  

---

## Repository Contents  
Note: Links provided are to the Google Drive / Colab versions so they can be continuously updated as necessary. Files uploaded to this repository were last updated: `12-7-2024`.

- **Data**:
  - [NWSL 2023 Season Data](https://drive.google.com/file/d/13yokJ4rb_op7ZjeLuJ4krzwJlLx2bz_E/view?usp=sharing)
- **Notebooks**:  
  - [Exploratory Data Analysis (EDA)](https://colab.research.google.com/drive/1Opg-MOMV9pBahe4VVe1ZDQ0svk3sh6ZC?usp=sharing)
  - [Model Development](https://colab.research.google.com/drive/14qxcJ8lKcxpN1f2QMaC6UpyB_gbq4GEo?usp=sharing) 
  - [Challenges Overview](https://colab.research.google.com/drive/1vnw_-4WoWkEvSS8rCZi0o8lJD2oFVG-o?usp=sharing) 

- **Final Report**:  
  - [PDF Summary Report](https://drive.google.com/file/d/1zh3HkkSgcmn8MjBxEXtfEy72GRC5-u7k/view?usp=sharing)  

---

## Highlights  

- **Manual Data Entry**: Addressed challenges with data accuracy, opting to focus on the 2023 season after initial plans to incorporate multiple seasons.  
- **Feature Selection**: Leveraged various techniques and standardization to determine key predictors.  
- **Model Optimization**: Employed tools like GridSearchCV for hyperparameter tuning.  
- **Dual Models**: Developed separate models to handle both granular (win/loss/tie) and broader (win/not win) classification tasks.  
- **Neural Networks**: Despite attempts to improve performance, neural network models were abandoned due to persistent overfitting and their inability to predict ties accurately.  

---

## Results  

- **Top Performers**: Logistic Regression and Decision Tree models demonstrated effective performance in both classification versions.  
- **Challenges**: Neural networks struggled with tie prediction and overfitting, leading to their exclusion from the final models.  

---

## Future Work  

- Incorporate data from multiple seasons to generalize results.  
- Explore team-specific variables to create tailored models.  
- Experiment with advanced machine learning techniques and additional datasets.  

---

## AI Disclaimer  

Generative AI tools were used to assist with:  
- Writing code for feature selection and grid search hyperparameter tuning.  
- Troubleshooting errors and brainstorming model improvements.  

All other code, analysis, and this report were authored by me. 
