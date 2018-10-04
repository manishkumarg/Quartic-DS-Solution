### <centre>Quartic-DS-Solution</centre> 

 __***Conceptual Approach***__ <br>

1- Understanding the problem and the dataset. <br>
2- Cleaning the dataset by handling missing values. <br>
3- Understanding the relation between different variables with the target field  using P-value and Pearson coefficient. <br>
4- Those fields which have high statistical significance are taken into consideration for predicting the target field. <br>
5- Two approach has been taken and various Machine Learning Algorithms has been applied to each approach , the algorithm with **better        score** which is **Decision Tree classifier** in this case has been used for Prediction. <br>
6- To check the accuracy of the prediction , further **Train-Test Split** is applied on the **data_train** and predicted target value is      compared with actual value.  <br>
7- The approch having **fewer number of difference between actual value and predicted value** is used for prediction , which is **Approach    2**  is taken into consideration i.e. only those **variables having high Statistical significance.** <br> 

__***Model Performance***__ <br>

As model is Decision Tree classifier :<br>
      1. Time Complexity <br>
         Assuming the worst case Scenario **O(mnlogn)** , which is for every node n we wil test m feature.<br>
         We can have time complexity by putting m=25 and n=892816 <br>
      
      2. Execution Time <br>
         The execution time can be calculated by importing timeit, which comes around 0.003561342499551756.
         
If I had more time , I would like to go in depth of each variable and its relation with target through visulaizayon techniques. I would have explore why Derived attributes are having low statistical significance and weak correlation with the target field. Also I would have tried to reduce the number of features. 
         
          
