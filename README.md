# Employee Attrition Classification using Scikit-Learn

<hr>
<h3>Data</h3>
https://www.kaggle.com/datasets/colearninglounge/employee-attrition
<br>

<hr>
<h2>Data Distribution</h2>
<div align=center>
<img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/56342543-7729-4908-a831-b96c87fbbe64" width="32%" height="32%" title="Without PolynomialFeature">
<img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/93467cfc-2499-4ad9-8041-1ef2ede2e85d" width="32%" height="32%" title="With PolynomialFeature">
<img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/9260cff9-b1b2-498b-ae85-db95995731df" width="32%" height="32%" title="With PolynomialFeature and Oversampling">
</div>
After preprocessing, the data distribution are shown in images above. <br>

<hr>
<h2>Classification Results</h2>
<div align=center>
<img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/cc800fc2-77fe-410f-a617-7f63fbd1449b" width="45%" height="45%"> &nbsp; &nbsp; <img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/d6f60689-bea0-4c20-aea1-a271913d17ed" width="45%" height="45%"><br>
Left: KNeighborsClassifier, Right: DecisionTreeClassifier <br> <br>

<div align=center>
<img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/59a3fe45-1014-426b-8075-945d28230088" width="45%" height="45%"> &nbsp; &nbsp; <img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/04194ff1-8ffe-4134-a92a-fe1c2479c44f" width="45%" height="45%"> <br>
Left: XGBClassifier, Right: GradientBoostingClassifier <br><br>
</div>

<div align=center>
<img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/24ba72ce-5e19-42a6-90c7-fd2bc9e1da48" width="45%" height="45%"><br>
RandomForestClassifier <br><br>
</div>

<hr>
<h2>Ensemble</h2>
<div align=center>
<img src = "https://github.com/mongshil553/Scikit-Learn-Classification/assets/129606995/8d4bf597-c5ef-43ee-b46b-ea07590480fb" width="45%" height="45%"><br>
Voting Ensemble using all of the model above. <br><br>
</div>
Through Voting Ensemble, Classification Precision has increased.
