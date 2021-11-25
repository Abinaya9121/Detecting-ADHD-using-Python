# Detecting-ADHD-using-Python
Machine learning project used to detect ADHD based on the given ADHD and Control text dataset. 

<li>The dataset used for prediction is ADHD dataset.
<li>At first, the matlab(.mat) files are converted to the csv file using scipy.
<li>Since, the number of rows in all the files are different, so minimum number of rows from the all the files is calculated and extracted only minimum number of rows in all the csv files.
<li>Then, mutual information for every subject was calculated and then calculated average mutual information for every feature in that mutual information matrix.
<li>Average mutual information of all the files are combined to a single dataframe.
<li>Class labels are also added to the corresponding rows(1 corresponds to ADHD and 0 corresponds to healthy control).
<li>Data visualization, like topoplot is displayed for each class in this notebook.
<li>Performed Principal Component Analysis(PCA) on the combined dataset and reduced the dataset to two dimension.
<li>Plotted the dataset to infer whether the dataset is linearly separable or not. Resulted in linearly non separable data.
<li>Then, optimum number of dimensions in PCA was found(optimum value is 5).
<li>Many Supervised and Unsupervised Learning Algorithms were used to build the model and compared all the models using different evaluation metrics.
<li>Trained the before combined data with different machine algorithms and performed different evaluation metrics.
<li>The table in the notebook shows all the accuracy score of the models and the respective model name.
