# Capstone Final Report
### Updated ML Model for Breast Cancer Tumor Diagnosis
![Tumor cell nucleus boundaries from the report by Street, Wolberg, & Mangasarian (1992).
](image.png)

At the time of the report by Street, Wolberg, and Mangasarian (1992), breast masses  were traditionally diagnosed by full biopsy, an invasive surgical procedure. Fine needle aspiration (FNA) allows doctors to take a much smaller tissue sample, but diagnosis based on an FNA sample was difficult because of the high number of nuclear features thought to be correlated with a malignant tumor. Street et. Al chose 3 features from the 10 obtained through FNA and developed a multi-surface method tree (MSM-Tree) model to classify the masses as malignant or benign. They achieved 97.3% accuracy, 90% sensitivity, and 86% specificity.  Although this model’s performance was strong, there is value in improving the sensitivity and specificity given the life-or-death, emotional, and financial implications of the results. 

With advent of random forest models, which were first described in 1995, there is potential to correctly classify tumors with even higher accuracy, sensitivity, and specificity. This project saught to do just that, building a Random Forest model with 98.25% accuracy, 97.62% sensitivity, and 97.62% specificity. 

**Some thoughts for future modeling:** I manually adjusted the probability threshold, to optimize sensitivity and specificity, but that may not be the best approach. It could be better to employ deep learning methods instead. I can revisit this after I finish my deep learning unit! :) 

