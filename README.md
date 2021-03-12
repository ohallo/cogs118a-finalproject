# cogs118a-finalproject

Due on March 17, 2021 11:59PM CA 

Replicate a subset of the experiment in ​https://www.cs.cornell.edu/~caruana/ctp/ct.papers/caruana.icml06.pdf

----CODING ----

Algorithms
1. Logistic Regression
2. Random Forest
3. KNN 
    - Hyper para:  K = |trainset| k=1,5,9,13,17,21,... 105

Datasets
1. LETTER (positive class A-M, negative class N-Z)
2. LETTER (positive class O, negative class all letters ≠ O)
3. Blood pressure https://archive.ics.uci.edu/ml/datasets/Cuff-Less+Blood+Pressure+Estimation
4. Eye https://archive.ics.uci.edu/ml/datasets/EEG+Eye+State

Error Metrics
1. ACC
2. F1
3. AUC

Results to record
1. Training results across all metrics
2. Testing results across all metrics 
3. ttest , p values

Bonus
1. Heat map of validation performance vs hyperparameter setting 
2. Mean ROC , PR curves

---- WRITING ---- 

1. Main 3 tables
2. Appendix 3 tables
3. >1000 words
4. Format: abstract, intro, method, experiment, discussion, 3 references (Journal of Machine Learning Research format / NeuriPS)


---- RANDOM ----








Datasets

1. Parkinsons https://archive.ics.uci.edu/ml/datasets/Parkinsons
2. Chess https://archive.ics.uci.edu/ml/datasets/Chess+%28King-Rook+vs.+King-Knight%29
3. Ecoli https://archive.ics.uci.edu/ml/datasets/Ecoli
4. Credit https://archive.ics.uci.edu/ml/datasets/Credit+Approval
5. Lung cancer https://archive.ics.uci.edu/ml/datasets/Lung+Cancer


Plan

Week 8 
(Mon/Tues/Wed) - attempt to recreate results for "Letter" 
    - data = https://archive.ics.uci.edu/ml/datasets/Letter+Recognition
(Thur/Fri) - do again for different data set(s) 
    - 7-10k samples
    
    
 
 Dataset 1:
 
 Some issues:
  - error metrics were not happening w/in the call
  - unregularized, regularized Logistic regression (separate) check 
  - SVM: different kernals (separate) ??

 
  - piazza post @611: "Note that GridSaerchCV saves all the metric values of all param settings. You can use that to retroactively find the best AUC params, train it up, get test set performance, then do it again on the ACC, etc." QUESTION = what do you mean by this - are we looking for the params that did best in training or testing?

 Answered:
  - KNN: K = |trainset| k=1,5,9,13,17,21,... 105 (which should be 26 values if I'm doing the math right)







