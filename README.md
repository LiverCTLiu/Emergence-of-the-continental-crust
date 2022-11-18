This repository contains data and python code used in the manuscript "Land Exposure Since the Early Archean Revealed by Machine Learning" by Chuntao Liu, C. Brenhin Keller, Xiaoming Liu, J ZhangZhou. This readme file also helps you conduct the python coding.

Contents:

1.Tables:

Table-S1.Parental traning dataset: The parental training dataset was compiled from the GEOROC database, which comprises basalt samples erupted subaerially or subaqueously in various tectonic settings.

Table-S2.Training dataset for XGBoost modeling: We extracted major and trace elements from the "Parental training dataset", which can be applied to train the XGBoost machine learning model.

Table-S3.Application dataset and predicted results of subaerial probability: The application dataset comprises the "KS2021" dataset and data from the EarthChem database. We have put the refined and unfined geochronological data in the dataset. Every sample's subaerial eruption probability, predicted by our well-trained XGBoost machine-learning model, was also listed in this file.

Table-S4.Application dataset for prediction: We extracted major and trace elements from the "Application dataset", which can be predicted by the well-trained XGBoost model.

Table-S5.Hydrothermally altered vs. unaltered basalts: Liu and He (2021) (doi: 10.7185/geochemlet.2115) compiled this geochemical data of hydrothermally altered and unaltered basalts. Then, we applied the XGBoost machine learning method to predict every sample's subaerial eruption probability. As a result, our model can accurately identify the sample's aquatic erupted environment despite the alteration of samples.

2.Codes:

Please put the Excel file and the python code in the same path.
All the python codes were implemented on the Jupyter Notebook platform.

If you want to run the "Python_code_1_XGBOOST-ctliu2022", you should use the Excel Table-S2 and Table-S4.
Please delete the first row of each Excel file before running. See details in the python file.

If you want to run the "Python_code_2_bootstrap-ctliu2022", you should use the Excel Table-S3.
Please delete the first row of the Excel file before running. See details in the python file.
