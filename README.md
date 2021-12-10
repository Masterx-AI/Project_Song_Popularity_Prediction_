# AI/ML Project: Song Popularity Prediction 🎷🎸🎹🎼
<p align="center"><img src="https://user-images.githubusercontent.com/54996245/145608240-38d9cd36-4fb2-4ea6-aaf6-abbc8446fa2d.jpg" style="width: 1000px;"/></p>

### Description:

Human's have greatly associated themselves with Songs & Music. It can improve mood, decrease pain and anxiety, and facilitate opportunities for emotional expression. Research suggests that music can benefit our physical and mental health in numerous ways. 

Lately a multiple studies have been carried out understand songs & it's popularity bases on certain factors. Such song samples are breaken down & their parameters are recorded to tabulated. Predicting the Song Popularity is the main aim.

The project is simple yet challenging, to predict the song popularity based on energy, acoustics, instumentalness, liveness, dancibility, etc. The dataset is large & it's complexity arises due to the fact that it has strong multicollinearity. Can you overcome these obstacles & build a decent predictive model?

**Source**
The dataset is taken from Kaggle:
https://www.kaggle.com/nicholasnisopoli/song-popularity-prediction/data

### Objective:
- Understand the Dataset & cleanup (if required).
- Build Regression models to predict the song popularity w.r.t a single & multiple feature.
- Also evaluate the models & compare thier respective scores like R2, RMSE, etc.

### Stractegic Plan of Action:
  
**We aim to solve the current problem statement by creating plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Feature Selection/Extraction
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:
**1. Target Variable Distribution**

<p align="left"><img src="https://user-images.githubusercontent.com/54996245/145608944-6aa51ca9-edb7-42a2-8525-8e864cfd1a67.png" /></p>

**2. Categorical Feature-set Distribution**
  
![image](https://user-images.githubusercontent.com/54996245/145608988-d08335b1-70e5-436f-9266-e8258efdac2a.png)

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/145609019-af47c18e-20fa-483b-a385-0c34912df74b.png)
![image](https://user-images.githubusercontent.com/54996245/145609030-592fd69f-d5eb-47d1-ad38-2d6b34f2a077.png)

**4. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/145626525-b34ae81d-ea66-46c3-8b62-ea5fba8775bc.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/145609168-9784b392-0f37-4926-beef-43d5a799b271.png)

**6. Correlation Plot**
  
![image](https://user-images.githubusercontent.com/54996245/145626386-090029e6-9aec-48ad-804e-f37ac2e0d2c1.png)

**7. Feature Selection/Extraction - VIF, RFE & PCA Techniques:

![image](https://user-images.githubusercontent.com/54996245/145609239-3f475842-b7fd-4e28-99f1-62412ea6c525.png)
![image](https://user-images.githubusercontent.com/54996245/145609258-538658b5-8c32-4615-b9ce-428cdc241088.png)
![image](https://user-images.githubusercontent.com/54996245/145609272-1b23fd01-1f0d-4e21-8707-2da0f82661f6.png)
![image](https://user-images.githubusercontent.com/54996245/145609301-6dd59dd4-470b-4198-b51e-8dc657fdd743.png)

**8. Multiple Linear Regression Prediction & Residual Normality Check**
  
![image](https://user-images.githubusercontent.com/54996245/145626263-903f493e-e304-488a-862e-54567af25eac.png)

**9. Polynomial Degrees Comparison**

![image](https://user-images.githubusercontent.com/54996245/145609472-55b87558-98e7-4ecf-b0cd-1b9094ad95d8.png)

**10. Predictions**

![image](https://user-images.githubusercontent.com/54996245/145609438-50087a5a-7013-49ee-828d-1355d80a7ce8.png)


**11. ML Algorithm's Scores Comparison (R2& RMSE) for the Ad Budge Dataset**

![image](https://user-images.githubusercontent.com/54996245/145609520-47928535-c007-486e-b14d-07f302db511c.png)
![image](https://user-images.githubusercontent.com/54996245/145609552-465cdf2b-fe99-42dc-8f4c-15522f7adaca.png)

### Here are some of the key outcomes of the project:
- The Dataset was large enough totally just 18835 samples & after preprocessing 52.5% of the datasamples were dropped. 
- Visualising the distribution of data & their relationships, helped us to get some insights on the feature-set.
- The features had high multicollinearity, hence in Feature Extraction step, we skipped as of now as Advanced Regression Alogrithms take care of it.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- While, Polynomial Regression (Order-2) was slightly overfitting, it is safe to use multiple regression algorithm, as their scores were quiet comparable & also they're more generalisable.
