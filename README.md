Overview:
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding
with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, 
you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations 
that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively

Results:
The target for this analysis is the column 'IS_SUCCESSFUL.'
The features for this model are: 
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, and ASK_AMT.
The variables that I got rid of are: EIN, NAME, and SPECIAL_CONSIDERATIONS

Compiling, Training, and Evaluating the Model:
How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used kerastuner to optimize the model.
Were you able to achieve the target model performance?
No, I was not able to.
What steps did you take in your attempts to increase model performance?
 I ran the data through several times, adding and removing features, which
sometimes caused the model to be overfit. I finally arrived at the given model, which is not optimal. 
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
This data is just not enoght to create a working and reliable model. I would recommend getting more usable data. This 
could be by gathering more data, or by reformating or binning the ASK_AMT column so the values are more usable. 
