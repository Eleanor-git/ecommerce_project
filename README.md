# End-to-End Customer Experience Enhancement Solution
## 應用「數位軌跡資料」協助**提升客戶體驗**

* Problem:
    * User Drop-off prediction based on **Sequence-based(next-step drop)** 
    * Classification Problem
      ```
        y = 1 → drop (下一步沒有任何event)
        y = 0 → continue
       ```    
    * User event sequence：
    | step t | step t+1 |
    | :---:| :---: |
    | view | view |
    | view | add cart |
    | view | add cart |
    | add | None (-> drop) |
  
* Goal:
    * User drop-off rate reduction
    * Coversion uplift

* Data
    * [Retailrocket recommender system dataset](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset)
    * 日期: 2015-05-03 到 2015-09-18之間
* Model:
    * Logistic Regression
       
* Metrics Evaluation:
    * AUC
    * Recall
    * F1-score