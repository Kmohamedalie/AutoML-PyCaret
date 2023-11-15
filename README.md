# Automated machine learning with PyCaret
**AutoML:** is the process of automating the tasks of applying [machine learning](https://en.wikipedia.org/wiki/Machine_learning) to real-world problems. The high degree of automation in AutoML aims to allow non-experts to make use of machine learning [wikipedia](https://en.wikipedia.org/wiki/Automated_machine_learning).
It started in the 1990s as a set of open source tools, like Weka, which helped research scientist and engineers automate tedious tasks, but gain popularity in 2020 which was due to the easy-to-use AutoML packages(python) and softwares development [Akkio](https://www.akkio.com/post/how-does-automated-machine-learning-work#:~:text=History%20of%20AutoML&text=It%20originated%20in%20the%201990s,development%20of%20more%20sophisticated%20techniques.).




#### A list of few **AutoML Systems 🤖:**
| [AutoWEKA](https://www.cs.ubc.ca/labs/algorithms/Projects/autoweka/) | [PyCaret](https://pycaret.org/) | [H20](https://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html) | [Auto-sklearn](https://automl.github.io/auto-sklearn/master/) |[Auto-PyTorck](https://github.com/automl/Auto-PyTorch) | [AutoKeras](https://autokeras.com/)|
| --------- |--------|-----------|----------|----------|----------|

However in this repository we will just focus on the PyCaret AutoML library but readers are free to explore the others. For the regression task, the [housing dataset](https://github.com/PacktPublishing/Practical-Data-Science-with-Python/tree/main/14-Chapter-14/data) has been used for performing EDA and ML-regression task, while the in-built "Credit default" dataset made possible by PyCaret was used for the classification task, finally the Clustering was perform using [Kmeans](https://en.wikipedia.org/wiki/K-means_clustering#:~:text=k%2Dmeans%20clustering%20is%20a,a%20prototype%20of%20the%20cluster.) and [palmer's penguin](https://rpubs.com/michelle10128/923430) dataset which is a good alternative to [Iris dataset](https://archive.ics.uci.edu/dataset/53/iris).


<br><br>


#### **Results and findings 🔍 (Supervised, Unsupervised learning algorithms):**
**1. [Regression](https://github.com/Kmohamedalie/AutoML-PyCaret/blob/master/Notebooks/PyCaret_Regression.ipynb)** - R<sup>2</sup>:  0.7746
   
![image](https://github.com/Kmohamedalie/AutoML-PyCaret/assets/63104472/dc5947a1-3b0b-4383-a6d0-11e413100eda)


<br>

   
**2. [Classification](https://github.com/Kmohamedalie/AutoML-PyCaret/blob/master/Notebooks/PyCaret_classification.ipynb)** Accuracy :   82.06% 

Note there are other metrics for evaluating the classifcation model depending on the application domain <br>
(precision, recall, F1-score, MCC) are all very useful.
   
![image](https://github.com/Kmohamedalie/AutoML-PyCaret/assets/63104472/aa060ad3-2657-4251-8a4c-41254fa564f8)


<br>
   
**3. [Clustering (Kmean - PCA, Elbow, Cluster distribution plot)](https://github.com/Kmohamedalie/AutoML-PyCaret/blob/master/Notebooks/PyCaret_Clustering.ipynb)**

**PCA plot:**

![newplot](https://github.com/Kmohamedalie/AutoML-PyCaret/assets/63104472/ea5bcc6d-7de6-4d19-a379-6eeb6312413a)


**Cluster distribution:**

![newplot (1)](https://github.com/Kmohamedalie/AutoML-PyCaret/assets/63104472/82883445-be72-4873-a22d-058aef549aea)


**Elbow plot:**

![image](https://github.com/Kmohamedalie/AutoML-PyCaret/assets/63104472/02e6b863-bf01-4bb6-af0b-6372d39b8ea5)





  



<br><br>

#### **Link to the notebooks:**     👉 [Here](https://github.com/Kmohamedalie/AutoML-PyCaret/tree/master/Notebooks)

<br>


#### **Further readings 📚:**
Utilize the code in the notebooks to explore and perform both classification, regression and clustering tasks.

[PyCaret](https://pycaret.gitbook.io/docs/): Automated Machine learning <br>
[YellowBrick](https://www.scikit-yb.org/en/latest/index.html): Machine learning visualizer <br>
[Medium](https://medium.com/@HeCanThink/clustering-with-pycaret-a-hands-on-example-92999de0f69a) : Clustering with PyCaret: A Hands-On Example in Python<br>
[Medium](https://alam-jane61.medium.com/classification-problem-with-pycaret-a0eb43a2f1ca): Classification problem with PyCaret <br>
[Pack Practical DataScience](https://www.amazon.com/Practical-Data-Science-Python-hands/dp/1801071977): AutoML with PyCaret chapter 14.

