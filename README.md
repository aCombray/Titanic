# Titanic

## Introduction
This notebook is a study of the Kaggle project <a href = "https://www.kaggle.com/c/titanic">Titanic: Machine Learning from disaster</a>. The goal is to understand and to develop a general workflow of machine learning problem.

## Thoughts
<ul>
<li> How to deal with ordinal features. The cutting into bands of 'Age' and 'Fare' is artificial in my opinion. For an ordinal feature, what people care is just the relative ranking. So the mean, normal distributions etc don't make sense. How to prepossess these features? I feel it is more appropriate to do a clustering of the data.
</li>
<li>
What to learn: 
How to study correlations of feature by ploting and visualization. 
</li>
<li>
Single feature correlated with the predition
</li>
<li>
Hard: Correlation between two features. This is to engineer new features from different features. 
</li>
<li>
Study all the models mentioned. Answer why some are appropriate / some are not appropriate. Can you explain/expect the performance scores?
</li>
</ul>

## References

This notebook has been created based on great work done solving the Titanic competition and other sources.

<ul>
  <li> 
  <a href = "https://www.kaggle.com/acombray/fork-of-titanic-data-science-solutions/editnb">Titanitc Data Science Solutions</a>
  </li>
  <li> 
  <a href = "https://www.kaggle.com/acombray/introduction-to-ensembling-stacking-in-pyth-238427/editnb">Introduction to Ensembling/Stacking in Pyth 238427</a>
  </li>
  <li>
  <a href = "https://www.kaggle.com/acombray/titanic-best-working-classifier/editnb">Titanic best working classifier</a>
  </li>
  <li>
  <a href = "https://www.kaggle.com/acombray/a-journey-through-titanic/editnb">A Journey through Titanic</a>
  </li>
</ul>
