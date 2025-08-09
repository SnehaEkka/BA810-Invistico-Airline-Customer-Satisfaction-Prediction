# Invistico Airline Customer Satisfaction Analysis  
#### Predicting and understanding factors influencing passenger satisfaction to enhance the in-flight experience

![](https://github.com/SnehaEkka/BA810-Invistico-Airline-Customer-Satisfaction-Prediction/blob/main/airline-banner.jpg)

### About  
This project analyzes airline customer satisfaction data from Invistico Airlines to uncover critical factors affecting passenger experience. Using machine learning classification models, it provides actionable insights and recommendations for improving service quality.

### Data Source  
- **Dataset:** Customer satisfaction data including flight and service ratings for over 120,000 flights.  
- **Source:** Public dataset from Kaggle by Yakhyojon [link to dataset]  

### Purpose & Business Context  
The airline industry faces fierce competition, where customer satisfaction is a key differentiator. However, passenger satisfaction depends on multiple subjective and objective factors. This project aims to identify which aspects of the flight experience most strongly influence satisfaction, focusing on factors controllable by the airline, to guide service improvements and maximize customer retention.

### Solution Overview  
Leveraging Python and machine learning classification algorithms, including Logistic Regression, Random Forest, and Support Vector Machines, this project builds predictive models to classify passengers as satisfied or dissatisfied. Data preprocessing, feature engineering, and model tuning techniques were employed to optimize performance and interpretability.

### Tech Stack & Tools

| Tool/Technology     | Role in Project                    | Why Chosen                                  |
|--------------------|----------------------------------|---------------------------------------------|
| Python             | Data cleaning, modeling           | Versatile, powerful analytics libraries     |
| Pandas & NumPy     | Data wrangling and manipulation  | Industry standards for structured data       |
| Scikit-learn       | Machine learning model building  | Comprehensive ML toolkit with easy API       |
| Matplotlib & Seaborn | Visualization and EDA            | Clear, insightful charts for data patterns  |
| Jupyter Notebook   | Interactive analysis and presentation | Transparency and reproducibility            |

### Data Pipeline & Workflow  
- Load and clean raw flight and satisfaction data, handling missing values and categorical encoding.  
- Perform exploratory data analysis to understand feature distributions and correlations.  
- Engineer features for improved model input quality.  
- Train multiple classification models (Logistic Regression, Random Forest, SVM) and evaluate based on accuracy, precision, recall, and ROC AUC.  
- Interpret model results to identify top factors influencing satisfaction.  
- Generate recommendations for airline service enhancements.

### Key Business Impact & Results

- **Model Performance:**  
  - Random Forest classifier achieved the highest balanced accuracy (~93.5%) and precision (~95%), indicating strong predictive power.  
- **Actionable Insights:**  
  - Service factors like seat comfort, in-flight entertainment, and online support were significant predictors of satisfaction.  
- **Strategic Recommendations:**  
  - Prioritize improvements in inflight services and booking convenience to boost customer satisfaction.  
- **Operational Efficiency:**  
  - Provides the airline with a data-driven framework to monitor and enhance flight experiences continuously.

### Code Highlights & How to Run

- **Highlights:**  
  - Robust data preprocessing pipeline with median imputation and one-hot encoding.  
  - Comparative modeling approach using cross-validation to select best hyperparameters.  
  - Detailed feature importance analysis to connect technical model outputs with business context.

- **How to Run:**  
  1. Clone the repository.  
  2. Install dependencies: `pip install -r requirements.txt` (include pandas, scikit-learn, matplotlib, seaborn, jupyter).  
  3. Open and run `Customer_Satisfaction_Invistico_Airline.ipynb` in Jupyter Notebook.  
  4. Follow notebook instructions to explore data and reproduce model training and evaluation.

### Future Improvements  
- Expand the feature set by integrating external data sources such as weather and flight delay causes.  
- Develop real-time satisfaction prediction dashboards for airline operations teams.  
- Implement automated retraining pipelines to ensure models stay current with changing customer preferences.

### Alignment to Career Vision  
This project encapsulates my dedication to creating scalable, interpretable data solutions that uncover clarity in complexity. By linking machine learning outputs to real business actions, it demonstrates my passion for empowering teams and driving operational excellence through analytics engineering.

### Coursework & Contributors
- **Coursework:** Built as part of the BA810 - Supervised Machine Learning course, focusing on predictive modeling and practical business insights.
- **Contributors:** Sneha Ekka, Aryan Kumar, Tanvi Sheth, Yifan (Eric) Bai  

## Presentation Deck
Refer to the [Invistico Airline Presentation Deck](https://www.canva.com/design/DAF2M464bfc/qcw90PV2Koq5dDgz4Jo-hg/view?utm_content=DAF2M464bfc&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hd84d887ac9) for summarized findings and recommendations
