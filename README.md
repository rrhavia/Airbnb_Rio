Cognitivo.ai DataScience Test

Predict the price of a given Airbnb establishment in Rio de Janeiro 

1) Modeling strategy:

Investigate how the price are correlated with qualitative and quantitative atributes.

For quantitative, like room type and neighbourhoods, is plotting a colour map with these atributes and the respective mean price

For quantitative, is calculate the correlation between price and other atributes an make a multivariate linear regression

2) Cost function:

Is a multivariate linear function

Price[atributes] = alpha + beta_i*[atribute_i]

3) Model Selection:

I choose KNN (K Near Neighbouhoods) from Sklearn library to split data into training data and test data to make a linear fit 


4) Validation of the model:

By comparing the predict price with the real price, which is roughly good.

I choose KNN because it is a simple and effective method


5) Evidence of the model:

In true, I don't have evidences which the model is good enought. I have to do a quantitative analysis about how neighbourhood and room type influency in Price.




 
