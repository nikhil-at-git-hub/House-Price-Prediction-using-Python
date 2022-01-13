# House-Price-Prediction-using-Python

Dataset: 30,000 rows with 25 columns

1 indicates that person was not able to pay back the loan
0 indicates that the person had paid the loan back

% split of o's and 1's is done so that we can analyze and decide our cut-off point

-> Categorical variables that present in the data in numerical form should be converted to names first and then into dummy codes eventually. (unless they are hierarchical in nature)

for example: If gender category is there and in the data it is present and 1's and 2's, this should again be converted into names first that is 'Male' and 'Female' and then into dummy codes. Otherwise the model will associate a beta coefficient with it which would convey a wrong information. 

