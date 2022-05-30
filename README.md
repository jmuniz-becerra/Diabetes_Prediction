# Diabetes_Prediction
Creation of a logistic regression model to predict whether a patient has diabetes.

Here I utilized a logistic regression model for the classification problem of predicting if a patient has diabetes or not. The logistic regression model performed with 78% accuracy utilzing features (BMI, Glucose, Pregnancies, and Diabetes Pedigree Function).

Consruction of predictive models in the healthcare setting is very helpful, especially when assessing if a patient is on course to possibly contracting a disease.

Feature selection included finding correlation between features and diabetes outcome (yes/no). Analysis led to selection of the four aforementioned features with Spearman Correlation scores of (.29, .46, .22, .17) respectively. Rest of the feature scores can be found in....cell # ...

Correlation calculations led to the dropping of 'Age' from the training model due to moderately high correlation with 'Pregnancies' (.54) and to help reduce collinearity.

Interestingly, through this analysis I found that the Diabetes Pedigree Function had the lowest Spearman Correlation score (.17) of the selected features. This is noteworthy because it raises the question of if the methodology needs to be reassesed and fine-tuned.

In addition, the finding of pregnancies having such a relatively strong correlation with diabetes outcome led me to pondering a few things. Would it be plausible to investigate the signaling pathway involved in the placenta development/maintenance for the possible finding of previously unknown factors involved in insulin resistance? Is it possible that these factors become active in pregnant women due to placenta development, but silently become active in non-pregnant women or men when insulin resistance develops?
