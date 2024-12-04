# CSCI_FINAL_PROJECT
# I used a breast cancer dataset to predict whether an individual who has breast cancer will be a victim of it again in the future or won't, based on variables such as inv-nodes, tumour size, menopausal status, tumour size, and age status.
# I have two jupyter files for data cleaniing and for my visuals. My visual file also includes my code for overfitting/underitting and my machine learnning models. I cleaned my breast cancer dataset by replacing missing values with the mode
# of the data, replaced any "?" with "Nan", defined categorical columns and mapped them to an integer value, and converetd the variable deg-malig to an integer. Not much data cleaning was needed considering the data was already standardized 
# well. IN my visuals file, I incorporated a pie chart, some bar graphs, a boxplot, and a correlation martix to display some data visualization with the breast cancer variables. I also incorportaed some machine learning code to was well as 
# a a graph that compares the accuracy scores for them: Logistic Regression, KNN, and Decision Trees. I included metriucs such as precision, f1 score, and recall while testing my models. And finally, I have some overfitting/underfitting code 
# thats applied to each of my machine learning models. In that code, I creat some graphs that display the models training and test scores before optimization occured. I even created a histogram that compares the testing and test scores for 
# each of my three machine learning models. I dont use this graph in my presentation but rather use it as a way for me to better see where my models stand in overfitting/udnerfitting after optimization is applied on them. I am heavy on the
# visuals so that I can see if my null or alternate hypothesis are proving to be true. But from my data analysis, I have determind that there is no difference between age status, menopausal status, tumor size, and the likelihood of breast 
# cancer reccurnece. This is mostly discovered from my correlation matruix, where there was very little correlation between my variables. My highest correlation score was 0.49 between inv-nodes and capsule nodes. Breast cancer reoccurnece is
# slim as only about 29% of people had breast cancer occur for them again
# 
