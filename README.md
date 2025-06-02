# Elevate-Labs-Task-05

In the above Taskfolder you can find all the necessary files regarding Task 5. In the Jupyter file 'task5_solutions.ipynb', I have implemented Decision tree classifier andrandom forest  analyzes the UCI Heart Disease dataset to predict cardiovascular disease. I have mainly used the scikit learn library in python for creating the decision tree classifier and random forests and evaluated the both.

#### Decision Tree Implementation: \
Trained an initial decision tree (max_depth=3) \
Visualized the tree structure using Graphviz \
Analyzed overfitting by testing depths (1-20): \
Identified optimal depth at 5 \
Added regularization (min_samples_split=20, min_samples_leaf=10, ccp_alpha=0.01) \

#### Random forest model
Trained ensemble of 100 trees with matching constraints
Achieved improved accuracy:
Training: 91.34%
Test: 89.76%

#### Feature importance analysis
Top 3 decision tree features: \
oldpeak (ST depression) \
cp \
ca \
Random Forest top features: \
ca \
thal \
cp

#### Cross Validation
Random Forest Cross-Validation Scores: [0.87195122 0.87195122 0.90243902 0.89634146 0.84756098] \
Mean Random Forest CV Accuracy: 0.8780 ± 0.0197 \
Confirmed Random Forest's superior robustness
