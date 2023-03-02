<h1> Title:Classify the location and it able to build or Not Using Machine Learning </h1> 
<br>

<h3> Overview:</h3>
<hr>
<h5>
The project help contraction worker to know the ground can build or can not build 
</h5>

In this project, we will determine which machine learning algorithm will be useful with this dataset.
<img src=untitled.png>
<br>

# Columns 
<hr>
- Customer name 
- project Type
- Project Budget
- Project Timeline
- Project Location
- Hire 
<br>
We repeat the same process for other models, I will be using Naive Bayes and Decision Tree models and Logistic Regression. Their respective scorer nodes will output the prediction and accuracy results.
<br>

# comparing The Result 

<img src=knime.png>
<br>

We use the Column filter and row filter nodes to get rid of the unneeded columns and rows and then use Column rename node to rename our column.

<img src=compare_result.png>

<br>

We can repeat the process for the other models.

<img src= all_model.png>

<br>

# Combining the results and comparing

We can use the Column Appender node to combine our adjusted results and combine it.
<img src=appender.png>
<br>

# Conclusion 
In this project, I used KNIME to determine which machine learning model is the most suitable to be used for the provided dataset.

# Author
Ahmad Waebeusar 
