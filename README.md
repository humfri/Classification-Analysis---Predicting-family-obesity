**Introduction**:
The classification analysis aims to determine whether an individual has a family history of overweight by considering a set of features, ranging from eating habits to lifestyle choices. Two classification methods are employed: Decision Tree and Random Forest. The Decision Tree Classification employs a supervised learning algorithm, utilising the scikit-learn Decision Tree Classifier. This classifier divides the dataset into subsets based on significant attributes, creating a tree-like structure for classification. In contrast, Random Forest Classification, an ensemble learning approach, combines predictions from multiple decision trees. The scikit-learn Random Forest Classifier creates a forest of decision trees trained on random subsets of the data, enhancing accuracy and robustness through aggregated predictions.

**Dataset**:
The dataset is sourced from the UCI Machine Learning repository, comprising 17 attributes and 2111 records spanning Mexico, Peru, and Colombia. It covers diverse aspects such as Eating Habits, Physical Condition, and Other Features, providing comprehensive insights into lifestyle and health factors. The "NObeyesdad" indicates obesity levels (Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II and Obesity Type III). Other features include Gender, Age, Height, Weight, Family History with Overweight, Frequency of consuming high-caloric food (FAVC), Frequency of vegetable consumption (FCVC), Number of main meals (NCP), Consumption of food between meals (CAEC), Daily water consumption (CH20), Alcohol consumption (CALC), Monitoring calories consumption (SCC), Frequency of physical activity (FAF), Time spent using technology devices (TUE), Mode of transportation used (MTRANS), Level of smoking (SMOKE), and Time using technology devices (TUE).

## Dependencies

Make sure to have the following Python libraries installed to run the code:

- [pandas](https://pandas.pydata.org/) (version >= 1.3.3)
- [seaborn](https://seaborn.pydata.org/) (version >= 0.11.2)
- [numpy](https://numpy.org/) (version >= 1.21.2)
- [matplotlib](https://matplotlib.org/) (version >= 3.4.3)
- [scikit-learn](https://scikit-learn.org/stable/) (version >= 0.24.2)
- [imbalanced-learn](https://imbalanced-learn.org/stable/) (version >= 0.8.0)

You can also install the required packages using the following command:

```bash
pip install pandas==1.3.3 seaborn==0.11.2 numpy==1.21.2 matplotlib==3.4.3 scikit-learn==0.24.2 imbalanced-learn==0.8.0

**Result**
1. Decision Tree Classification Results:
 On Testing Set:
 Precision: 93.29%
 Accuracy: 86.05%
 Recall: 89.21%
 F1 Score: 91.21%

2. Random Forest Classification Results:
 On Testing Set:
 Precision: 94.51%
 Accuracy: 87.94%
 Recall: 90.38%
 F1 Score: 92.40%

**Conclusion**
The classification analysis successfully predicts family obesity using both the Decision Tree and Random Forest classifier models. Random Forest which is an ensemble of decision trees, demonstrates better performance on various metrics compared to the individual Decision Tree. The two models exhibit strong generalization capabilities as evident from cross-validation results. However, the presence of overfitting signals the necessity for fine-tuning or exploring additional techniques to enhance model robustness. Considering the context of the problem, future iterations may involve feature engineering and hyperparameter optimization to further improve predictive accuracy. The analysis and results provide valuable insights into the classification task and can guide future refinements for better model performance.


