# elec4840final
# This repository is a backup version of the final report, pls refer to SONG Shiyuan's canvas upload for the full report
# Only have half of the code - semi-supervised learning with pseudo-label by AU-YEUNG Yin Michael
code in final.ipynb

Background:
Skin lesions are abnormal areas on the skin, which can take the form of lumps,
sores, or changes in color or texture. Non-cancerous (benign) and cancerous
(malignant) are the two main categories for these lesions. While malignant lesions
have the potential to invade surrounding tissues and travel to other parts of the
body. It is essential that lesions be classified so as to address cancer growth.
Improvement has been make to the baseline model for better accuracy

Methodology:
semi-supervised learning with pseudo-label has been implemented.

Procedure:
Based on the baseline model trained, we generate predictions to unlabeled data and assign pseudo labels to them
group the train set with the new pseudo-labeled data to form a larger train set
train the model again with the larger trainset and old val and test set.

Result:
There is a rise of 0.07 in maximum accuracy compared to the baseline and baseline with semi-supervised learning with pseudo-label
