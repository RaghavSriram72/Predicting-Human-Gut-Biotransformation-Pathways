
The goal of this project is to predict what happens to chemical compounds when they interact with thehuman gut microbiome. In the gut, microbes break down and modify compounds through a series of
chemical reactions, resulting in new molecules called metabolites. Understanding these changes is essential for drug development, assessing chemical safety, and personalized medicine. Our system will take in the chemical structure of a compound and predict the sequence of transformations it undergoes, identifying the most likely pathways and end products.

Directory Organization:
project.html: File contains all the output of our notebook
project.ipynb: File contains the notebook where we performed all of our computational tasks
test.csv: File contains testing data. Test dataset includes the starting metabolite and the ending metabolite our model is supposed to predict.

In Archive folder:
test_demo.csv: Contains an example of how test data looks like. There are three columns, PWY_ID, Steps, and Compound
train.csv: Training set which consists of a list of metabolic reactions (17,320 reactions total)

IMPORTANT INFO: project.ipynb takes 1-2 minutes when run on a GPU but takes around 8 minutes when run on CPU only.
