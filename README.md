# OpenCV-img-classification
The dataset for this machine learnig/data science project consists of Images of popular footballers using Fatkun 
chrome extension that is a webscrapping tool.Once the dataset is ready,opencv library
is used to detect faces and eyes before cropping them.Then feature engineering
is performed using wavelet transformations.since the dataset is quite varied 3 models 
are built for analysis namely SVM,Logistic regression,Random Forest Model.The models are fine tuned using gridsearchCV
and the best estimate is exported to a .pkl file.The accuracy of the best estimate is
is visulised with a confusion matrix.GridsearchCv is used to tune the model.
