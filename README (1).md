# 102103611-Parameter-Optimisation-in-SVM

# Dataset

This assignment focuses on utilizing a multi-class Support Vector Machine (SVM) model on the Adult Census Income dataset sourced from the UCI Machine Learning Repository. The dataset comprises 15 columns and 32,561 rows.

The Adult Census Income dataset provides insights into individuals' demographics, including age, education level, marital status, occupation, and whether their annual income exceeds $50,000.

For model training and evaluation, the dataset was split into a 70-30 ratio for training and testing, respectively. To optimize the SVM model, a grid search approach was adopted, exploring 1000 iterations with randomly sampled values of C and gamma within the range of 0 to 1, alongside different kernel functions. This optimization process was conducted across 10 distinct samples of the dataset.

Throughout the optimization procedure, the highest accuracy achieved and the corresponding SVM parameters were recorded for each dataset sample.
# Result

<img width="494" alt="image" src="https://github.com/Codelord2003/102103058-Parameter-Optimisation-in-SVM/assets/95679005/647c2d98-f29c-43b5-a6af-e28f40da25e5">

# Graph

<img width="570" alt="image" src="https://github.com/Codelord2003/102103058-Parameter-Optimisation-in-SVM/assets/95679005/305146e0-2312-4c67-9c55-bdadc8571df1">

# Conclusion
We get the Sample 2 with the highest accuracy of 0.8
