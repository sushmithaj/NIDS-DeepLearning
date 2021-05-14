# NIDS-DeepLearning
Network Intrusion Detection System using Deep Learning
1. Created a non symmetric auto encoder based on [1]
2. Trained auto encoder on KDD-Cup '99 [2] dataset for feature extraction
3. Used the features extracted and trained a Random Forest Classifiers with Forest Value set to 200
  1. Used the trained data to create two classifiers including a 5-class classification and a 13-class classfication
4. Achieved 97% Accuracy.
5. Created Confusion Matrix, Calculated : Accuracy, Precision, Recall, F1-Score, ROC-AUC Score. 

### References
[1] N. Shone, T. N. Ngoc, V. D. Phai and Q. Shi, "A Deep Learning Approach to Network Intrusion Detection," in IEEE Transactions on Emerging Topics in Computational Intelligence, vol. 2, no. 1, pp. 41-50, Feb. 2018, doi: 10.1109/TETCI.2017.2772792.
[2] https://www.kaggle.com/galaxyh/kdd-cup-1999-data
