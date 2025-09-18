**Advanced Pattern Recognition Project**  

This project focuses on **predicting the rating of a movie** based on key features extracted from a movie dataset. It demonstrates feature reduction using PCA and prediction using linear regression.

---

## Dataset

The dataset contains multiple features about movies, including:  

- **Popularity** – The popularity of the movie among audiences  
- **Vote Count** – Number of votes received  
- **Rating** – Average rating of the movie  
- **Other Features** – Genre, release date, budget, revenue, runtime, etc.  

> Note: Only a subset of features is used for prediction in this project.

---

## Aim

The primary goal of this project is to **predict the rating of a movie** based on a few key parameters after reducing dimensionality.

---

## Procedure Followed

1. **Feature Reduction**  
   - Applied **Principal Component Analysis (PCA)** to reduce the number of features.  
   - Normalized the dataset and selected **2 principal components** for further analysis.

2. **Model Building**  
   - Built a **Linear Regression** model using the reduced features.  

3. **Visualization**  
   - Plotted the decision boundary and visualized predictions on the principal components.  

---

## Tools & Technologies

- **Programming Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Environment:** Jupyter Notebook / VS Code  

---

## Future Enhancements

- Include more features such as cast, crew, and reviews  
- Experiment with other regression models (Ridge, Lasso, Random Forest)  
- Develop an interactive web application for real-time rating predictions  

