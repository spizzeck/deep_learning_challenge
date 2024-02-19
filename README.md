Alphabet Soup Neural Network Model
Overview
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Through the use of machine learning and neural networks, the features in the provided dataset were used to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years was obtained. After obtaining the data it was preprocessed. The preprocessing helped determine what the target variable and the feature variables were for the model. After the data was preprocessed, the model was compiled, trained, and evaluated. Once this step was completed it gave us a start or a base to work with. From there we attempted to optimize the model to get above seventy five percent accuracy. 
Results
Data Preprocessing
•	Target variable for this model is the “IS_SUCCESSFUL” column
•	Feature variables for this model are:
o	APPLICATION_TYPE—Alphabet Soup application type
o	AFFILIATION—Affiliated sector of industry
o	CLASSIFICATION—Government organization classification
o	USE_CASE—Use case for funding
o	ORGANIZATION—Organization type
o	STATUS—Active status
o	INCOME_AMT—Income classification
o	SPECIAL_CONSIDERATIONS—Special considerations for application
o	ASK_AMT—Funding amount requested
•	The columns dropped for this model were “EIN” and “NAME.”
Compiling, Training, and Evaluating the Model
•	The model was tested three different times to try and obtain an accuracy of seventy five percent. 
•	The second model tested was the closest to the goal. The model was named “deep_nn_model_1.” It had three layers. Each time a layer was added the neurons decreased by half. The activation “relu” activation model was used for the densest layer and the “sigmoid” activation model used for each layer after. 
•	Unfortunately, the goal accuracy of seventy five percent was not reached. Model “deep_nn_model_1” only achieved an accuracy rating of 72.48%. 
Summary
From Alphabet Soups company a CSV file containing for than 34,000 organizations was obtained. The data was preprocessed. After preprocessing the data was compiled, trained, and evaluated. Three different models were made to obtain an accuracy score of above seventy five percent. 
Unfortunately, none of the three models were able to obtain an accuracy score of seventy five percent or greater. To achieve this goal if seventy five percent there are a couple of things that could be done. One of the things that could be done is eliminating or dropping more columns of the feature variables. Another thing that could be done is to add more neurons in the early layers. Lastly, if these options fail one could also decide to use a different model altogether other than neural networks. 
