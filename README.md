Data Analysis and Visualisation also was conducted..# Superhero_text_mining
Explorative data anlysis, extraction key information from text, classification with use of Naive Bayens, SVM, KNN, DummyClassifier, NearestCentroid with hypertuned parameters.  


# Set up
To run the notebook:
1. Upload notebook file to Google Colab or Jupyter Notebook
2. Eventualy change a path to data file
3. Start work with notebook


# About dataset
In the file superheroes.xlsx, informations about 1908 superheroes has been placed. Most of the superheroes are described by 80 features, however there are also NaN values or misplaced values. 

# The goal
The goal of the anaysis was to classify the heroes from data set into three categories (based on the information placed in columns 'power text' and 'history text'). To simplyfy classification only three creators where chosen 'DC Comics', 'Marvel Studios', 'other creator'.

# About notebook
In the notebook you can find proccesses of:
- data cleaning,
- data preprocessing,
- data vectorization,
- data transformation to tfidf matrixes,
- hypertuning classification with gridsearch,
- classification of dataset with hypertuned parameters.
- additional gridsearch and classification with hypertuned parameters on set with additional features. 


To save aplication from data leakage sklearn pipelines has been aplied.
