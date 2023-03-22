#

Name(s): Jade Zhou / Zeyang Yu


---

## Framing the problem

In this project,We aim to predict the calorie content of each recipe, which is a regression problem. The response variable we are predicting is "calorie", chosen because it is an essential aspect of the nutritional value of a recipe. Understanding calorie content helps users make informed decisions about the meals they prepare or consume, as it allows them to manage their daily calorie intake and maintain a balanced diet.

The features we include in the model are "fat" and "sugar", as these are the variables that typically have the most significant influence on calorie content. Moreover, these two variables are readily available when the recipe is published, making them practical choices for predicting the calorie content.

##  Baseline Model:

We created two baseline models to predict the calorie content of recipes, one using a Decision Tree Regressor and the other using a Linear Regression model. After comparing their performances, we determined that the Linear Regression model better predicts our data.

The two features we use in our model are the amounts of fat and sugar in the recipes.Both of these features are quantitative, as they represent numerical values. There are no ordinal or nominal features in the baseline model.

By using the Decision Tree model, we obtained an R^2 score of 0.70. However, when using the Linear Regression model, the R^2 score increased to 0.79, which is clearly higher. Therefore, we chose the Linear Regression model as our preferred baseline model due to its better performance in explaining the variance in the calorie content based on the fat and sugar features.
