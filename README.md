# Deploy-ML-model-with-Dockers-using-Breat_cancer-dataset

-Run Basic ML algo on Breast Cancer dataset.
-I have used Random Forest Classifier.

-Save the model in Pickle.
-Add Flask API information while prediction of test files.


-Flask file containes the following files 1) Flask_prediction.py 2) cancer_rf.py 3) requirements.txt
-Docker_file is individual file with no datatype description.

-Note:comments used in cmd prompt
-1) docker ps
-2) docker images
-3) docker run -p 5000:5000 rf-api
-4) docker run -t rf-api .

Run the following command
->cd 'content/sample_data/Docker sample/'
->docker built -t rf-api .
->docker run -p 5000:5000 rf-api

