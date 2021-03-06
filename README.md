# [SimplyHired Data Science Jobs Exploratory Data Analysis](https://github.com/michaelabryant/simplyhired-eda)
- Scraped and cleaned 1342 job postings consisting of 422 variables from SimplyHired.com
- Performed an exploratory data analysis to determine the most frequently posted job titles, qualifications, and job benefits
- Regressed salary onto 986 predictors, and used a Bonferroni correction to determine statistically significant predictors and their impact on salary

<br/>
<div align="center">
<figure>
<img src="images/job-titles-salary.jpg"><br/>
</figure>
</div>
<br/><br/>

# [Predicting Heart Disease in Patients with Angina](https://github.com/michaelabryant/heart-disease-prediction)
- Created nine classification machine learning models to make a prediction of heart disease using 303 patient records and 12 features
- Performed an exploratory data analysis and feature engineered a categorical risk factors variable based on high cholesterol, high blood pressure, high fasting blood sugar, and age for increased risk for each sex
- Hyperparameter tuned the models with a five-fold cross-validation and, for the best model, obtained a recall of 85.5% from the test set
- Deployed the best model with a [front-end](https://app-heart-disease-predictor.herokuapp.com/) hosted on a cloud application platform which can be used by doctors for evaluating patients

<br/>
<div align="center">
<figure>
<img src="images/heart-disease-deployment-larger.gif"><br/>
</figure>
</div>
<br/><br/>

# [Concrete Compressive Strength Prediction](https://github.com/michaelabryant/concrete-strength-prediction)
- Created four regression models to make a prediction of concrete compressive strength using 1030 concrete samples and nine features
- Performed an exploratory data analysis and feature engineered dummy variables for categorical data
- Hyperparameter tuned the models with a five-fold cross-validation and, for the best model, obtained an MSE of 17.56 MPa<sup>2</sup> and R<sup>2</sup> score of 0.93 from the test set
- Deployed the best model with a [front-end](https://predict-compressive-strength.herokuapp.com/) hosted on a cloud application platform which can be used to predict concrete compressive strength for civil engineers.

<br/>
<div align="center">
<figure>
<img src="images/concrete-frontend.gif"><br/>
</figure>
</div>
<br/><br/>

# [Bird Identifier App](https://github.com/michaelabryant/bird-identifier)
- Created a convolution neural network to classify photos of birds based on species using 39364 photos and 275 species
- Selected pre-trained model for transfer learning based on initial performance
- Hyperparameter tuned the selected model and modified model architecture to increase accuracy to 96.9%
- Deployed the front-end with Flask on my local machine which can be used by users to upload photo of birds for identification

<br/>
<div align="center">
<figure>
<img src="images/bird-deployment.gif"><br/>
</figure>
</div>
