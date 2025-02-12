# **Data-Mining-for-Customer-Satisfaction-Analysis-on-Airline-Passenger-Satisfaction-Survey**

## **Project Overview**
This project focuses on analyzing airline passenger satisfaction using data mining techniques. The study evaluates multiple factors, including delays, in-flight services, cleanliness, and other service parameters, to determine their impact on customer satisfaction.

## **Dataset**
The dataset includes various passenger details such as:
- **Demographics**: Age, gender, type of travel  
- **Flight Details**: Class, flight distance, departure/arrival delays  
- **Service Ratings**: In-flight service, cleanliness, food & drink, seat comfort, baggage handling, etc.  
- **Satisfaction Level**: Overall satisfaction (Satisfied/Neutral or Dissatisfied)  

## **Key Analysis & Techniques**
- **Data Preprocessing**: Handling missing values, discretizing numerical data, and transforming features.  
- **Exploratory Data Analysis (EDA)**:  
  - Statistical insights on departure and arrival delays.  
  - Distribution analysis of various features.  
  - Correlation between different parameters.  
- **Hypothesis Testing**:  
  - Influence of in-flight service quality and delays on passenger satisfaction.  
  - Effect of arrival delays on medium-haul passengers.  
  - Custom hypothesis testing on short-haul passengers.  
- **Association Rule Mining**: Using Apriori algorithm to uncover relationships between passenger attributes and satisfaction.  
- **Principal Component Analysis (PCA)**: Dimensionality reduction to find key satisfaction factors.  
- **Regression Analysis**: Relationship modeling between flight distance, delays, and satisfaction.  
- **T-Tests & Correlation Analysis**: Examining relationships between gender, travel type, and satisfaction.  

## **Project Structure**
```plaintext
📂 Airline-Passenger-Satisfaction
│── 📜 SONTIREDDY_FINAL_PROJECT_REPORT.docx  # Detailed project report
│── 📜 PROJECT.ipynb                          # Jupyter Notebook with code and analysis
│── 📜 README.md                              # Project documentation (this file)
```

## **Requirements**

To run this project, install the required libraries:  

```bash
pip install numpy pandas seaborn scikit-learn statsmodels matplotlib
```

**Usage**

  - Open PROJECT.ipynb in Jupyter Notebook.
  - Follow the step-by-step analysis, from data preprocessing to visualization.
  - Run hypothesis tests and regression models to understand key insights.

**Results & Insights**

  - Long-haul passengers value in-flight service quality more than departure delays.
  - Medium-haul passengers are more impacted by arrival delays than in-flight entertainment.
  - Short-haul passengers prioritize cleanliness over entertainment.
  - Business class travelers have significantly higher satisfaction levels than economy travelers.
  - Regression analysis found no significant relationship between flight distance and delays.

**Conclusion**

This analysis provides valuable insights for airline companies to enhance passenger experience by focusing on factors like in-flight services, cleanliness, and minimizing delays.
