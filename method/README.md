
## Research Method
- **Objective:** The objective of this research is to determine whether environmental and lifestyle variables can accurately predict the level of lung cancer.The specific research question aims to investigate the relationship between obesity levels and the incidence of lung cancer, utilizing machine learning techniques. Research shows that there's a nuanced relationship between obesity and lung cancer (Vedire et al., 2023), and obesity can be a potential risk factor for lung cancer in certain populations(Gupta et al, 2014). Some research found that "abdominal obesity" is very likely to play an important role in the development of lung cancer (Hidayat et al., 2016). By analyzing a dataset obtained from Kaggle, the objective is to determine if there is a discernible pattern or correlation between different levels of obesity and the likelihood of developing low, medium, or high levels of lung cancer. This research seeks to contribute to the understanding of how obesity, as a modifiable risk factor, interacts with the development and severity of lung cancer.
  
- **Significance:** This question is crucial in the field of public health and oncology as it can provide insights into the potential risk factors associated with different levels of lung cancer. Understanding the predictive power of environmental and lifestyle variables can aid in early detection, personalized treatment planning, and preventive strategies, ultimately improving patient outcomes and reducing the burden of lung cancer on society.

**Operational Measures:**

- **Variables:** The dependent variable (Y) in this study is the level of lung cancer, categorized into different stages or severity levels. The independent variables (X) include environmental factors such as air pollution levels, smoking habits, and occupational exposures, as well as lifestyle factors such as dietary patterns, physical activity levels, and socioeconomic status.

- **Data Type:** The dataset used for this research is likely to be cross-sectional, as it captures observations of individuals at a single point in time. Each observation includes information on the level of lung cancer and the corresponding environmental and lifestyle variables.

**Hypothesis Development:**

- **Prediction Hypothesis:** It is hypothesized that certain environmental and lifestyle variables, such as high levels of air pollution, smoking, and low socioeconomic status, will be positively associated with higher levels of lung cancer. Conversely, factors like healthy dietary patterns and regular physical activity may be negatively associated with lung cancer severity.

- **Justification:** This hypothesis is based on existing literature suggesting that environmental and lifestyle factors play significant roles in lung cancer development. Studies have consistently shown associations between air pollution, smoking, socioeconomic status, and lung cancer risk. Therefore, it is reasonable to expect that these variables may also predict the severity of lung cancer.

**Machine Learning Algorithm Selection:**

- **Algorithm:** Logistic Regression is selected as the machine learning algorithm for testing the hypothesis. Logistic Regression is well-suited for binary classification tasks, making it appropriate for predicting the levels of lung cancer, which can be categorized as low or high. Additionally, Logistic Regression provides interpretable results, allowing for the identification of significant predictors and the estimation of their effects on the outcome variable. Therefore, it is a suitable choice for examining the relationship between environmental and lifestyle variables and lung cancer severity.

## machine Learning methods
**Model Development:**

*Data Processing:*
To accurately quantify the variables of interest, the data underwent several preprocessing steps. Firstly, the "level" variable representing lung cancer severity was converted into numerical values (0 for low, 1 for medium, and 2 for high). Additionally, duplicates and missing values were checked and addressed to ensure data integrity.

*Results Presentation:*
The results will be presented through a comprehensive analysis of the predictive accuracy of logistic regression models for different groups of variables. Specifically, the focus will be on smoking-related factors (including smoking and passive smoking), environmental factors (such as occupational hazards and air pollution), and lifestyle-related variables (including alcohol consumption and balanced diet). Additionally, the combined effect of all these variables on predicting lung cancer levels will be examined. The results will be illustrated through confusion matrices to provide a clear visualization of the model's performance.

*Data Visualization:*
To effectively convey key insights, the results will be visualized using confusion matrices. These matrices will display the number of true positives, true negatives, false positives, and false negatives, allowing for a comprehensive understanding of the model's predictive accuracy for each group of variables and their combinations.

*Model Evaluation:*
The evaluation criteria for assessing the model's performance will include accuracy, precision, recall, and F1-score. These metrics will provide a holistic assessment of the model's ability to correctly predict lung cancer levels based on different sets of variables. Additionally, iterative model refinement strategies will be employed to enhance predictive accuracy. This may involve feature selection techniques, parameter tuning, and exploring alternative machine learning algorithms to optimize model performance. Through iterative refinement, the goal is to continually improve the model's predictive capabilities and provide more accurate insights into the relationship between environmental, lifestyle factors, and lung cancer levels.

### Flowchart
![image](https://github.com/Rising-Stars-by-Sunshine/STATS201_Jiahe_Final/blob/5c496a810e37c543953113f5c17ac95f0a6fcd5c/method/method%20markmap.png)

### Data Source
- https://www.kaggle.com/datasets/rishidamarla/cancer-patients-data



### Reference
- Vedire, Y., Kalvapudi, S., & Yendamuri, S. "Obesity and lung cancer-a narrative review." Journal of Thoracic Disease 15, no. 5 (2023): 2806-2823. https://doi.org/10.21037/jtd-22-1835.

- Hidayat, K., Du, X., Chen, G., Shi, M., & Shi, B. "Abdominal obesity and lung cancer risk: Systematic review and meta-analysis of prospective studies." Nutrients 8, no. 12 (2016): 810-810. https://doi.org/10.3390/nu8120810.

- Gupta, S., Hassan, S., Bhatt, V. R., Abdul Sater, H., & Dilawari, A. "Lung cancer trends: Smoking, obesity, and sex assessed in the Staten Island University's lung cancer patients." International Journal of General Medicine 7, no. default (2014): 333-337. https://doi.org/10.2147/IJGM.S55806.

- Stevens, M., & Nguyen, M. T. "Liver cancer remains a leading cause of cancer-related mortality worldwide." HEM/ONC Today 18, no. 22 (2017): 74-74. https://doi.org/10.1001/jamaoncol.2017.3055.

- Gandhi, Z., Gurram, P., Amgai, B., Lekkala, S. P., Lokhandwala, A., Manne, S., Mohammed, A., Koshiya, H., Dewaswala, N., Desai, R., Bhopalwala, H., Ganti, S., & Surani, S. "Artificial intelligence and lung cancer: Impact on improving patient outcomes." Cancers 15, no. 21 (2023): 5236. https://doi.org/10.3390/cancers15215236.

