## Step 3
In step3 , I deployed a DecisionTreeClassifier for first 10000 rows of G2M Data. 
I cleaned & preprocessed G2M data, 
and took only 4 the most relevant columns & 10000 rows for Model Deployment due to performance concerns of my GPU and easy-to read format of my deployment on Flask.
I developed DecisionTreeClassifier by setting the metrics of max_depth=8, min_samples_leaf=17, min_samples_split=7,random_state=42 because
this values points the best performance for my model according to the TPOT Classifier. I added relevant code (TPOT Classifier) as `TPOT.ipynb`

## Step 4
In this step, I deployed my model in step 3 with Flask. During my deployment, I also applied my HTML & CSS knowledge to design my API's fronted. You can find my API's local host version in ` screenshots.pdf`
* `model.pkl` points out my model that is deployed by Flask
* `temp.py` points out the temp file for Flask Deployment
* `index.html` points out the html code for the Model Deployment on Flask. It is in the `template` folder.
* `style.css` points out the CSS code for styling to my deployment. It is in the `static/ css`folder.
* `entry.png` is the png file that I used as the background image of my API.

