# human emotion classifier using classical machine learning methods &amp; face recognition
in this project i was about studying classical machine learning models by creating simple classifier between 7 human emotions (neutral, anger, contempt, disgust, fear, happiness, surprise). main goal of the algorithm is to predict the emotions on a person's face photograph using some labeled dataset. 

in this case i'm taking dataset containing human faces photographs where they were asked to show 7 emotions -> preparing it for machine learning methods (cropping, augmentation, histogram equalization) -> extracting gabor features -> applying PCA+LDA combo -> using some basic ml models (dt, rf, adaboost, gradient boosting, svm, knn and naive bayes) 

![photo-emotion](https://github.com/whyclos/emotion-recognition/raw/main/gabor-filters.png)

## sharing the dataset 
folder with images you can download [here](https://drive.google.com/drive/folders/1WNOIE0lshN97fioiFPMMkeEAUn5iunb8?usp=share_link)

[here](https://docs.google.com/spreadsheets/d/1fqFqaDujaNYzPwFPxgRbHiPfUAyxSBer/edit?usp=share_link&ouid=115557877886304897153&rtpof=true&sd=true) is labeled dataset as .xlsx file as a *label* - *filename* table 

the only problem about dataset used is disbalance in quantity of photoghaphs in different emotions samples (there are much more neutral examples) and that is why i used augmentation
