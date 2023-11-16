# Project 3 Reflection  
Rachel and I were working with the dataset from Behavioral Risk Factor Surveillance System survey conducted by the CDC in 2015. Our goal was to select a model for each level of education (1,3,4,5,6) that is the best at predicting whether an individual would or would not have diabetes/prediabetes. We did this by first training 6 different model types: Logistic Regression, Lasso, Classification Tree, Random Forest, Logistic Model Tree, and Partial Least Squares and choosing the best within each model type. We then used log loss for selecting *the best* model.  
  
If I were to start this project over, I would include a corrplot during EDA for more educated variable selection.  
The most difficult part for me was determining how to calculate the log loss metric for each model and the final model selection. I also struggled with the github pushes. The guidance provided on the yellowdig page regarding the logloss metric was very helpful. Luckily, Rachel was much more comfortable working with github.    
The big take-aways from this project for me was the efficiency of using machine learning and of using github to automate the creation of the github pages. I can't imagine how much more time and effort would have been needed to create the same output without the caret package and automation of the github pages.  
  
link to nicely render repo: https://rsfellman.github.io/ST558_Project3/  
link to github repo: https://github.com/rsfellman/ST558_Project3/tree/main  
