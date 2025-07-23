
# Bozeman Housing Price Prediction

This project uses web-scraped real estate data from Zillow to build a machine learning model that predicts home prices in **Bozeman, Montana**, a fast-growing and changing housing market. The workflow includes scraping raw data, cleaning and engineering features, encoding categorical variables, and applying machine learning models to estimate property prices.

---

## What This Project Covers

-  **Data Collection**: Web scraping Zillow search and listing data  
-  **Data Cleaning**: Filtering relevant property features, handling missing values, formatting columns  
-  **Feature Engineering**: Standardizing "levels", one-hot encoding, and selecting important variables  
-  **Modeling**: Building and evaluating models (e.g., Random Forest, XGBoost) for price prediction  
-  **Evaluation**: Comparing R² and accuracy metrics to choose the best-performing model

---

## Technologies Used

- Python (Jupyter Notebook)  
- Pandas and NumPy for data manipulation  
- Seaborn and Matplotlib for visualizations  
- Scikit-learn for model training and evaluation  
- XGBoost for gradient boosting regression

---

##  Dataset

- **Source**: Web-scraped from Zillow using Python (search results and listing pages)  
- **Location**: Bozeman, MT and surrounding area  
- **Features**:
  - Address, City, Zipcode, Latitude, Longitude  
  - Home features: Bedrooms, Bathrooms, Living Area, Lot Size  
  - Boolean tags: FSBA, FSBO, New Home, Foreclosure  
  - Style: `levels`, `homeType`, `homeStatus`, etc.

---

## Example Data Cleaning

- Mapped raw values like `"1.0"`, `"two"`, `"Multi/Split"` into standard categories (`One`, `Two`, `Three Or More`, `Split`)  
- One-hot encoded categorical fields such as `"levels"` and `"homeType"`  
- Dropped rows with missing target values (`price`)

---

## Project Outcomes

- Developed a functioning end-to-end price prediction model  
- Built from self-collected data, demonstrating initiative and technical skill  
- Best R² from tuned Random Forest and XGBoost models exceeded **0.81**  
- Identified key features driving price, including:
  - Living area  
  - Location (latitude/longitude)  
  - Bedrooms & bathrooms  
  - Home type and status

---

## Lessons Learned

- Strengthened skills in **web scraping** and cleaning inconsistent real estate data  
- Improved proficiency in **feature encoding**, especially for complex categorical variables  
- Gained experience comparing model performance metrics like **R² vs accuracy**  
- Learned how to build a project with both **analytical rigor** and **visual storytelling**

---

## Author

**Ian Barriger**  
_Data Science Undergraduate | Class of 2027_  
Focused on real-world ML applications and predictive modeling with web-scraped data  

 [LinkedIn](www.linkedin.com/in/ianbarriger) •  [Portfolio](ianjbarriger.github.io/portfolio/) •  [GitHub](https://github.com/IanJBarriger)
