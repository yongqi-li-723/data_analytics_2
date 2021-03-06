# Python assignments and Projects:

1. In **Unit 2**, we learned about the basics of Python, such as list, dictionary, and build-in functions. We also learned about for loop, if-else statement, and so on. 

   a. [Link to the assignment file](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_2/Unit_2_lesson_2%263%264%265%266.ipynb)
   
   b. We have two mini projects for this unit.
      - Check if the input is odd or even, if it is multiple of 4. More generally, define a function that takes in two numbers and check whether the first number is divisible by the second. 
      - Rock, paper, scissor game: define a function that takes two inputs and determine who wins. 
      - [Link to the project file](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_2/Python_Project_Odd_or_Even_and__Rock_Paper_Scissors.ipynb)
      
2. In **unit 3**, we learned about the functions within *numpy*, *pandas*, and *matplotlib* packages. We see examples of data wrangling and data visualization. 
   
   a. In [assignment 1](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_3/Unit3_NumPy_Assignment_1.ipynb), I practiced using *numpy* package to find the maximum within an array, and subset array according to certain criteria. 
   
   b. In [assignment 2](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_3/Unit3_Python_Advanced_Pandas_DataWrangling_Assignment.ipynb), I did data analysis using salaries dataset. I calculated mean, median, and I did basic data transformations on the dataset, such as rename and subset columns. I visualized the dataset by making scatter plots and histograms. Lastly, I draw conclusions based on the plots. 
   
   c. The project for this unit is on the hot topic of the year, COVID 19. The codes for the first 4 tasks were set up clearly. After carefully reading all the codes and statements, I did some analysis on the states that have high death case. I answered the following questions:
   
      - Which five states have the highest number of death?
      - Analysis of COVID 19 in the 5 states since December 22nd. 
      - A different approach to calculating new cases. 
      - [Link to the project file](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_3/COVID19_DATA_ANALYSIS.ipynb)
3. In **Unit 4**, we learned about Machine Learning. More specifically, we learned various ML methods such as *linear regression*, *logistic regression*, *K-Nearest Neighbors*, *decision trees*, and *random forest*. 

   a. We use linear regression to predict Boston housing prices. I got $RMSE=4.64$ and $R^2=0.69$. The outcome was not satisfying, and I was able to get a better result with decision trees. [Linear regression Notebook](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/Linear_Regression_Boston_Housing_Guided_Project.ipynb)
   
   b. We worked on two examples on using logistic regression. We learned about the confusion matrix, the difference between recall, precision, and accuracy, what is ROC-curve, and how to interpret it.    
   
      - [Predict survival with Titanic dataset](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/Logistic_Regression_Titanic_Class_Notes.ipynb)
      - [Predict ad clicking behavior with advertising dataset](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/Logistic_regression_predict_ad_click.ipynb)
      
   c. We use `Classified` dataset to examine KNN method. We learned about how to standardize data, how different K-values change predictions, and how to pick the right K-value.
      - [Predict class with classified dataset](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/KNN_with_Classified_dataset.ipynb)
      
   d. Decision trees can be used on both classification and regression problems. 
      - [Re-predict ad clicking behavior with advertising dataset with decision trees](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/Decision_Tree_Classification.ipynb): in this example, the decision trees model did not return a higher score than the logistic model.
      - [Re-predict Boston housing price with decision trees](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/Decision_Tree_Regression.ipynb): R-squared went from 0.69 to 0.78 when using decision trees. 
      
   e. Random forest: I re-predicted ad clicking behavior by using a random forest classifier, and I worked out another example found at DataCamp.com on the famous iris dataset. I re-predicted Boston Housing price by using a random forest regressor and got $R^2$ = 0.87 (significantly better than other methods). I worked on another example of predicting temperature. 
   
   We worked **Amazon Alexa review project**. From this project, I learned about how to do one-hot encoding using `get_dummies`, and how to convert a column that contains sentences, e.g., reviews,  into numerical values using `CountVectorizer` and understand the idea behind the algorithm. I learned about feature importance and understand that fewer features can improve our model's performance since there is less noise. I also looked into the learning curve of my models to see if feeding more data to the model can improve performance. 
      - [Re-predict ad clicking behavior and example from DataCamp](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/Random_forest_classification.ipynb)
      - [Re-predict Boston Housing price and predict tempuratue](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/Random_forest_regression.ipynb)
      - [Amazon Alexa review project](https://github.com/XiaonaZhou/data_analytics_2/blob/main/Python/Unit_4/Amazon_Alexa_Review_RandomForest_Classifications_Guided_Project.ipynb)
