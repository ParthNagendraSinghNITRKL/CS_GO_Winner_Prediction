# CS:GO 
### Terrorists v/s Anti Terrorists

"Counter-Strike: Global Offensive" (CS:GO) is the fourth game in the Counter-Strike series. In CS:GO, the format of the game is 5v5 players who take turns playing one of 2 sides: terrorists(T) or counter-terrorists(CT). In competitive gameplay, games are played best of 30 rounds(a tied score that would lead to overtime would be 15-15 for example). The object of the game for the Ts to get to A or B site and plant the bomb until it goes off. The CTs will try to defuse that bomb. The round ends when one of those conditions is met, or when the full 5 team members on the opposing side are dead. 
___

### Analysis
+ In this project, I have analyzed a large dataset of the game in `python` to predict the winner in different circumstances.
+ I carried out `data preprocessing`, `Exploratory Data Analysis(EDA)`, `Principal Component Analysis(PCA)` and finally winner prediction after thorough `model selection`.
___

### Questions Answered
1. What maps are popularly played in the professional scene?
2. What maps have a round favor toward CT vs T side?
3. Method of winning a match.
4. Match winner prediction with more than 80% accuracy.
___

### Results
+ Chose the best ML classification model among `Logistic Regression`, `K-Nearest Neigbours`, `Support Vector Classifier` and `Random Forest Classifier`.
+ Went ahead with the **Random Forest Classifier**.
+ Without hyperparameter tuning, got an **f1 score** of **83.33%** for the model.


 (**Note**: The code to hyperparameter tune the model is mentioned in my code, it just takes a huge amount of time to do so!)
___


### Scope for improvement
+ Outlier detection and removal.
+ Using different scalers to transform data and then do predictions
+ Using other model selection parameters such as auc-roc curve to determine best model.
___

[Link](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbktfSlVGR3NyZXFkMFZHaERyWUZVaVg1R3NvUXxBQ3Jtc0tta0c5WFNUMkNVV2hFSFhZVmdBUHhtZHdsbVUyTFI0aDlFRG4wSFBYLVM4UnlrUUdCMlJiTE1ocTVWTm1sVDAtSUhseTk3ZWNwSlJVZVEzSzkxckcwS2hhckRLRk16QW5jZHE2NnJMRWZ2NG9OcWxfcw&q=https%3A%2F%2Fwww.kaggle.com%2Fchristianlillelund%2Fcsgo-round-winner-classification&v=DAS0M0Q2Jn8) to the kaggle dataset used.
