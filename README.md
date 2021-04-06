In Week 4, I deployed a DecisionTreeClassifier for first 10000 rows of G2M Data. 
I cleaned & preprocessed G2M data, 
and took only 4 columns & 10000 rows for Model Deployment due to performance concerns of my GPU and easy-to read format of my deployment on Flask.
I developed DecisionTreeClassifier by setting the metrics of max_depth=8, min_samples_leaf=17, min_samples_split=7,random_state=42 because
this values points the best performance for my model according to the TPOT Classifier. I added relevant code (TPOT Classifier) as `TPOT.ipynb`
* `model.pkl` points out my model that is deployed by Flask
* `temp.py` points out the temp file for Flask Deployment
* `index.html` points out the html code for the Model Deployment on Flask
* `style.css` points out the CSS code for styling to my deployment. 
* Outcome of my Model Deployment on Flask can be seen in the `screenshotsformodel.pdf` file.
