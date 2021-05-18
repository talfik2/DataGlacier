## Step 1
* In the first step, I merged the relevant tables and examined our data.
## Step 2
* In the second step, I preprocessed data, and make it ready for further steps.
* In these two steps, I used following methods:

* Joining tables <br>
 pd.merge
* Preprocessing <br>
 SimpleImputer with Most Frequent Strategy as it accepts the categorical values <br>
 Normalization as our problem is classification & there are lots of unique values
* Feature Extraction <br> PCA; plotting features & PCA's n_components for 90 % usefulness
* Outlier Detection <br> Matplotlib's boxplot
* Outlier Elimination <br> Quantile Based Outlier Elimination Technique
