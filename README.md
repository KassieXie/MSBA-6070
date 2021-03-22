# MSBA-6070
 Including class assignments and other course related work
 
# CA5 A - Logistic Regression

*Background:* Cardiovascular Disease (CVD) kills more people than cancer globally. A dataset of real heart patients
collected from a 15 year heart study cohort is made available for this assignment.

**Goal:** 


Part 1: build a binary classifier model to predict the CVD Risk (Yes/No, or 1/0) using a Logistic
Regression Model with the best performance possible (deliverable: Notebook)

Part 2: Display the Feature Importance of all the features sorted in the order of decreasing influence on
the CVD Risk (deliverable: Notebook)

Part 3: Evaluate the performance of your model (including ROC Curve), explain the performance and
draw a meaningful conclusion. (deliverable: Performance outputs in Notebook, explanation and
conclusion in Word/PDF document)

*Dataset:* 
The dataset has 16 patient features. Note that none of the features include any Blood Test information.

The file location is https://raw.githubusercontent.com/ArinB/CA05-B-Logistic-Regression/master/cvd_data.csv. You can directly input the location in the codes, or use the file I provided in the folder with my codes.

The following is a description of columns:

•	cvd_4types: Label Column. 0 indicates “No Risk”, 1 indicates “Risk Present”

•	age_s1: Age in Years

•	race: 1 - White, 2 - Black, 3 – Other

•	educat: Education level (Sleep Heart Health Study Visit One (SHHS1))

•	mstat: Marital Status (Sleep Heart Health Study Visit One (SHHS1))

•	hip: Hip Circumference (Sleep Heart Health Study Visit One (SHHS1))

•	neck20: Neck Circumference (Sleep Heart Health Study Visit One (SHHS1))

•	waist: Waist Circumference (Sleep Heart Health Study Visit One (SHHS1))

•	av_weight_kg: assumebly average weight in kg

•	cgpkyr: Cigarette pack-years (Sleep Heart Health Study Visit One (SHHS1))

•	tea15: Health Interview (Sleep Heart Health Study Visit One (SHHS1)): cups of tea on a regular day

•	srhype: Self-reported hypertension (HTN) (Sleep Heart Health Study Visit One (SHHS1))

•	parrptdiab: History of Diabetes (Sleep Heart Health Study Visit One (SHHS1))

•	bend25: Quality of Life (QOL) (Sleep Heart Health Study Visit One (SHHS1)): Health limits bending, kneeling, or stooping

•	happy25: Quality of Life (QOL) (Sleep Heart Health Study Visit One (SHHS1)): Been a happy person

•	tired25: Quality of Life (QOL) (Sleep Heart Health Study Visit One (SHHS1)): Felt tired

•	hlthlm25: Quality of Life (QOL) (Sleep Heart Health Study Visit One (SHHS1)): Health limited your social activities



## Assignment Requirements

1. Build a binary classifier model
2. Display the Feature Importance of all the features
3. Evaluate the performance of your model

## Language 

The programming language: Python 3

The file format: ipynb 
- Any application that can open .ipynb file will be great, but I highly recommend using Google Colab or Ananconda Jupyter Notebook.

The comment and text language: English 

## Packages Installed 
Python packages: 
all sorts of packages including numpy, sklearn, and so on.

- The codes include installing packages are already embeded in this notebook. It shouldn't have problem if you run my code step by step. 

## Expected Outcome
The expected outcome should already be displayed in the notebook under the codes, but feel free to test the code on your own.

## Logic Behind
Logistic Regression is a Machine Learning classification algorithm that is used to predict the probability of a categorical dependent variable. In logistic regression, the dependent variable is a binary variable that contains data coded as 1 (yes, success, etc.) or 0 (no, failure, etc.). In other words, the logistic regression model predicts P(Y=1) as a function of X.

All formal sources related to logistic regression linear model provided by scikit-learn developers can be found at: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html

## Contributing
Apologize in advance that any pull requests other by the host might be rejected because this is an education repository for personal use. 

Still, welcome to open an issue if you have something want to discuss, or directly contact with me via my email (xxie3@lion.lmu.edu).
