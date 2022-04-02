# Deep Learning Homework: Charity Funding Predictor

1. **Overview** of the analysis: Explain the purpose of this analysis.

The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful

2. **Results**: Using bulleted lists and images to support your answers, address the following questions.

  * Data Preprocessing
    * What variable(s) are considered the target(s) for your model? The target of my model was the Column "IS_SUCCESSFUL", as this is the final objective we want to be able to predict, all the other columns where the features for my model, except for invaluable data contained in the "EIN" and "NAME" columns, these were droped in the preprocessing process.

For this model we used two hidden layers, the first one with 80 neurons and using the "tanh" activation method and the second hidden layer had 30 neurons and used the relu activation method, although it is not recommended to use different activation methods  in the same model and the recommendation accordding is: "In modern neural networks, the default recommendation is to use the rectified linear unit or ReLU …" — Page 174, Deep Learning, 2016. Being this a challenge I decided to mix and match to see what happened. This might be one of the reasons the objective of getting an 80% accuracy was missed, perhaps changing the activation method and adding several more epochs would generate a better performing model.
- - 
