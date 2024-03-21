# Credit Risk Classification
A challenge using sci-kit learn's train_test_split to train and evaluate a model based on loan risk. The dataset is historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Data Collection and Preprocessing
The datasets used for analysis were provided by edX Boot Camps LLC, and are intended for educational purposes only. I used pandas to load the csv data into a dataframe.

## Methods
I imported essential dependencies like pandas, numpy, and sklearn. After loading the CSV into a pandas dataframe, I separated the target (y) from the features (X). Then I used sklearn's train_test_split module to split my data into training and testing sets. I used the LogisticRegression model on the training data to split results into binary classifications. From there, I used the results of that to predict results using the testing data. I then applied a confusion matrix to the testing data predictions and printed the report to review precision and recall.

## Conclusion
The classification report shows healthy loans have a 100% precision and recall rate for prediction. However, for predicting hihg-risk loan labels, the precision and recall rates are at 87% and 89% respectively. So the model is not as effective at labeling high-risk loans correctly.

![classification_report](https://github.com/ASPigman/credit_risk_classification/assets/145923874/07cb910f-99b0-438a-97e2-16d10f1e4b0e)

## Acknowledgements
Othmane Benyoucef - Instructor for Tulsa Community College Data Analytics Accelerated Training Program

Kaylie Butler - TA

Jacob Peroutek - TA

EdX Bootcamps
