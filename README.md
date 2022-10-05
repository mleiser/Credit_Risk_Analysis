# Credit_Risk_Analysis

## Overview of the Analysis
  
### Purpose
  The purpose of this challenge was to use six different machine learning algorithms to test credit risk and how accurate each model is. The results are to be compared to each other to determine which algorithm performs the best for the given data set. This is done using python and imbalance-learn and scikit-learn libraries for the machine learning.
## Credit Risk Analysis Results
  ![Naive Random Oversample](https://user-images.githubusercontent.com/46801182/193965784-cf3a48cc-83b0-422e-99b2-73357b873f7d.png)
  ![image](https://user-images.githubusercontent.com/46801182/193966328-837e7689-96cd-4c99-baf9-945a1b37409e.png)
  - Naive Random Oversampling showed a low precision for high_risk while a very high precision for low_risk points. It also showed a higher recall value in low_risk than in high_risk. It also had a decent accuracy.
  ![SMOTE Oversampling](https://user-images.githubusercontent.com/46801182/193966095-c147656b-5a9a-4fd5-81b1-ef4b6331d055.png)
  ![image](https://user-images.githubusercontent.com/46801182/193966304-ba6866d6-6f4f-4f13-a8a9-a36714de3522.png)
  - SMOTE Oversampling showed very similar values to Naive Random with the main difference being the recall being closer together. It has a higher accuracy than Naive though.
  ![Undersample](https://user-images.githubusercontent.com/46801182/193966409-22198d46-cc7b-4d6c-ad5b-164c1e0ff15f.png)
  ![image](https://user-images.githubusercontent.com/46801182/193966466-703bd41f-c0b8-48a0-b4d7-1e558e841f35.png)
  -Undersampling showed a higher recall with high_risk points than low_risk while having a lower accuracy when compared to the oversampling algorithms.
  ![SMOTEENN](https://user-images.githubusercontent.com/46801182/193966596-03b50bb8-214a-4aa8-8384-03ac33255efa.png)
  ![image](https://user-images.githubusercontent.com/46801182/193966637-b880e593-2d21-4663-9124-6f094eb26d46.png)
  - The combined algorithm showed a much higher recall for high_risk compared to low risk. It also had an accuracy value comperable to Naive oversampling.
  ![Random Forest](https://user-images.githubusercontent.com/46801182/193966933-ec86074e-6f77-4cd6-9a49-12b1c54e9399.png)
  ![image](https://user-images.githubusercontent.com/46801182/193967049-d09dbf92-947e-4a91-9942-d9f60d343b88.png)
  - Random forest algorithm shows that it has a much higher accuracy than any of the previous algorithms while also having high recall and a higher precision score for high_risk that still isn't great.
  ![Easy Ensemble](https://user-images.githubusercontent.com/46801182/193967784-4fd0cb0b-b782-42c1-821b-72444195a0a3.png)
  ![image](https://user-images.githubusercontent.com/46801182/193968022-bd8b938e-859c-48a4-b536-58cfc446a686.png)
 - Easy Ensemble has the highest accuracy of any algorithm tested and the highest recall and precision.
## Credit Risk Analysis Summary
  When looking at the results of the testing, some models performed much better than others. I would have to recommend Easy Ensemble as a good algorithm to use due to the high recall, accuracy and precision scores when compared to all the other algorithms. I would say to avoid SMOTE oversampling as an algorithm due to having the lowest accuracy score and a bad precision score on top of it. The rest of the algorithms were relativily comperable to one another.
