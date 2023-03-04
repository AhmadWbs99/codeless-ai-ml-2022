<h1> Title:Classify the location and it able to build or Not Using Machine Learning </h1> 
<br>

<h3> Overview:</h3>
<hr>
<h5>
The project help contraction worker to know the ground can build or can not build 
</h5>

In this project, we will determine which machine learning algorithm will be useful with this dataset.
<img src=all_nodes.png>
<br>

# Columns 
<hr>
<ul>
<il>Customer name</il> 
<il>project Type</il> 
<il>Project Budget</il>
<il>Project Timeline</il>
<il>Project Location</il>
<il>Hire</il>
</ul>
 
<br>

# Methods 
As our dataset is formatted in Excel, it is necessary to employ the Excel reader node to gain access to the data.
<image src=reader.png>

# Data understanding
<img src=FirstML.png>

First we connect Excel Reader into Column Filter to choose what's columns do you want to use , and then connect to Number To String node to change number into string , after that connect to Missing Value for cleaning missing data , Next connect to Partitioning node for setup how many persentage let machine learning do , afterword connect into Decision Tree Learner for learn Machine Learning , after that connect into Decision Tree Predictor , and then connect to Missing Value node to clean missing data.

also , is the same things about two models.
<image src=ML_nodes.png>

# comparing The Result 

<img src=knime.png>
We repeat the same process for other models, I will be using Naive Bayes and Decision Tree models and Logistic Regression. Their respective scorer nodes will output the prediction and accuracy results.

<br>

We use the Column filter and row filter nodes to get rid of the unneeded columns and rows and then use Column rename node to rename our column.

<img src=compare_result.png>

<br>

We can repeat the process for the other models.

<img src= Scores.png>

<br>

# Combining the results and comparing
We can use the Column Appender node to combine our adjusted results and combine it.
<img src=appender.png>
<br>

# Conclusion 
In this project, I used KNIME to determine which machine learning model is the most suitable to be used for the provided dataset.

# Author
Ahmad Waebeusar 
