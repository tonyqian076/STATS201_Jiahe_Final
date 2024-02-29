# Relationship between Obesity and Lung Cancer: a Machine Learning Method

## Research Question Formulation

### Objective
The specific research question aims to investigate the relationship between obesity levels and the incidence of lung cancer, utilizing machine learning techniques. Research shows that there's a nuanced relationship between obesity and lung cancer (Vedire et al., 2023), and obesity can be a potential risk factor for lung cancer in certain populations(Gupta et al, 2014). Some research found that "abdominal obesity" is very likely to play an important role in the development of lung cancer (Hidayat et al., 2016). By analyzing a dataset obtained from Kaggle, the objective is to determine if there is a discernible pattern or correlation between different levels of obesity and the likelihood of developing low, medium, or high levels of lung cancer. This research seeks to contribute to the understanding of how obesity, as a modifiable risk factor, interacts with the development and severity of lung cancer.

### Significance
Understanding the association between obesity and lung cancer is of paramount importance in public health and oncology. Lung cancer remains one of the leading causes of cancer-related deaths worldwide (Stevens & Nguyen, 2017; Gandhi et al., 2023), and its incidence is influenced by various factors, including lifestyle choices such as obesity. Investigating this relationship can provide insights into potential preventive measures and interventions to reduce the burden of lung cancer. Furthermore, given the rising prevalence of obesity globally, elucidating its impact on lung cancer risk can inform targeted strategies for cancer prevention and management. Therefore, this research holds significance in advancing knowledge about the complex interplay between obesity and lung cancer, with implications for public health policy and clinical practice.

## Operational Measures
### Data Source
- https://data.world/cancerdatahp/lung-cancer-data
- https://www.kaggle.com/datasets/rishidamarla/cancer-patients-data
### Variables
- Dependent Variable (Y): The incidence or severity of lung cancer, categorized as low, medium, or high.
- Independent Variable (X): Levels of obesity, classified on a scale of 1 to 9, as provided in the dataset.

### Data Type
The dataset used for this analysis is cross-sectional, as it represents a snapshot of individuals' characteristics (obesity levels) and outcomes (lung cancer incidence) at a specific point in time.

## Hypothesis Development

### Prediction Hypothesis
It is hypothesized that higher levels of obesity will be associated with an increased likelihood of developing lung cancer and/or experiencing more severe forms of the disease. Specifically, individuals classified with higher obesity levels (e.g., scores 7-9) may exhibit a higher prevalence of medium to high levels of lung cancer compared to those with lower obesity levels.

### Justification
This hypothesis is grounded in existing literature that suggests a potential link between obesity and lung cancer risk. While the exact mechanisms underlying this association are complex and multifactorial, obesity is known to induce chronic inflammation, alter hormonal profiles, and impact immune function, all of which may contribute to carcinogenesis in the lungs.

## Machine Learning Algorithm Selection

To test the hypothesis and analyze the relationship between obesity levels and lung cancer incidence, an appropriate machine learning algorithm will be selected. Given the nature of the dataset (predicting a categorical outcome based on numerical predictors), a supervised learning algorithm such as logistic regression or random forest classification may be suitable. The choice of algorithm will depend on the complexity of the data and the need for interpretability versus predictive accuracy.

## The Machine Learning Workflow

### Model Development

#### Data Processing
The dataset will be preprocessed to handle missing values, normalize or standardize features, and encode categorical variables (if any). Additionally, feature engineering techniques may be employed to create new variables or transform existing ones to improve model performance.

### Results Presentation

#### Training and Testing
The dataset will be split into training and testing sets to train the machine learning model on a subset of the data and evaluate its performance on unseen data. The split ratio will typically be around 70-30 or 80-20, ensuring an adequate balance between training and evaluation.

#### Data Visualization
Various visualization techniques, such as histograms, scatter plots, and confusion matrices, will be utilized to visually explore the relationships between variables and assess the model's predictive performance. This will facilitate the interpretation of results and the communication of key findings.

### Model Evaluation

#### Evaluation Criteria
Performance metrics such as accuracy, precision, recall, and F1 score will be used to evaluate the model's ability to predict lung cancer incidence based on obesity levels. Additionally, receiver operating characteristic (ROC) curves and area under the curve (AUC) scores will assess the model's discriminatory power.

#### Iterative Improvement
The model will undergo iterative refinement through techniques such as hyperparameter tuning, feature selection, and cross-validation to enhance its predictive accuracy and generalizability. Feedback from model evaluation metrics will guide the adjustment of model parameters and strategies for improving performance.

### Flowchart
![image](https://github.com/Rising-Stars-by-Sunshine/STATS201_Jiahe_PS2/assets/154964920/6aaa4edd-8130-4d36-adb6-9a024c051391)


### Reference
- Vedire, Y., Kalvapudi, S., & Yendamuri, S. "Obesity and lung cancer-a narrative review." Journal of Thoracic Disease 15, no. 5 (2023): 2806-2823. https://doi.org/10.21037/jtd-22-1835.

- Hidayat, K., Du, X., Chen, G., Shi, M., & Shi, B. "Abdominal obesity and lung cancer risk: Systematic review and meta-analysis of prospective studies." Nutrients 8, no. 12 (2016): 810-810. https://doi.org/10.3390/nu8120810.

- Gupta, S., Hassan, S., Bhatt, V. R., Abdul Sater, H., & Dilawari, A. "Lung cancer trends: Smoking, obesity, and sex assessed in the Staten Island University's lung cancer patients." International Journal of General Medicine 7, no. default (2014): 333-337. https://doi.org/10.2147/IJGM.S55806.

- Stevens, M., & Nguyen, M. T. "Liver cancer remains a leading cause of cancer-related mortality worldwide." HEM/ONC Today 18, no. 22 (2017): 74-74. https://doi.org/10.1001/jamaoncol.2017.3055.

- Gandhi, Z., Gurram, P., Amgai, B., Lekkala, S. P., Lokhandwala, A., Manne, S., Mohammed, A., Koshiya, H., Dewaswala, N., Desai, R., Bhopalwala, H., Ganti, S., & Surani, S. "Artificial intelligence and lung cancer: Impact on improving patient outcomes." Cancers 15, no. 21 (2023): 5236. https://doi.org/10.3390/cancers15215236.

