# Reddit Flare Detector Web App

Hosted @ : https://reddit-flare-detector.herokuapp.com/

Journey/ Details of the Data/Machine Learning models : https://github.com/YatinGupta777/Reddit-flare-detector

This app takes a Reddit Post as Input and then predicts a flare for it. 

Analyzed over 400,000+ r/india posts.

Details of ML model used here :

1. SVM : Parameters : C=1.0, kernel='linear', degree=3, gamma='auto'
2. 11 target variables.
3. Trained on ~3k Posts per flare
4. Accuracy : 54%
5. Performs well on any reddit post, not necessarily r/india.
