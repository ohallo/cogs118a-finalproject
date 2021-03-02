# cogs118a-finalproject

Due on March 17, 2021 11:59PM CA 

Replicate a subset of the experiment in ​https://www.cs.cornell.edu/~caruana/ctp/ct.papers/caruana.icml06.pdf

Algorithms
1. Logistic Regression
2. SVM
3. KNN



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







