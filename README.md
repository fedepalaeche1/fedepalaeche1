- š Hi, Iām @fedepalaeche1
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
fedepalaeche1/fedepalaeche1 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 Import KNeighborsClassifier from sklearn.neighbors
from sklearn.neighbors import KNeighborsClassifier
--->
Create arrays for the features and the response variable
y = df['party'].values
X = df.drop('party', axis=1).values
--->
Create a k-NN classifier with 6 neighbors
 knn = 6 
 knn=KNeighborsClassifier(n_neighbors=6)
--->
Fit the classifier to the data 
knn.fit(X,y)
