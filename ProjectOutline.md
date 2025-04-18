## CPSC 419 Project Outline

---

1. __Dataset__
    
   - The [diamonds dataset](https://github.com/mwaskom/seaborn-data/blob/master/diamonds.csv) from [Seaborn](https://github.com/mwaskom/seaborn-data) will be used
<br>
  
2. __Data Cleaning__

   - As of currently, NaN/Null values will be dropped from the table.
<br>

3. __Supervised Learning__

   - Using linear regression to determine the classification of the diamonds in the given set
   - Will be trained using simple train/test
   - Will be measured via a confusion matrix
<br>

4. __Unsupervised Learning__  - James Heathcock

   - The algorithms used will be:
     1. Mean Shift
     2. DBSCAN
     3. Gaussian-Mixture Model
   - If dimensionality reduction is needed, then random projection will likely be used.
<br>    

```mermaid
graph TD
Diamonds[Diamonds] --> split(train_test_split)
split --> dtrain[diamond_train]
split --> dtest[diamond_test]
dtrain --> scan{DBSCAN}
dtrain --> shift{MeanShift}
dtrain --> gmm{GMM}
```

5. __Wrap-up__/__Conclusions__

6. __References__
<br>

---
#### Contributors
 - James Heathcock
 - _Add Name_
