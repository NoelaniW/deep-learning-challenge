Module 21 Analysis Report

Overview:
    The purpose of this analysis is to predict whether applicants for funding will be successful if funded by Alphabet Soup.

Results:
    -Target variable for the model was IS_SUCCESSFUL.
    -Features variables for the model were Application type, affiliation, classification, use case, organization, income amount, and special considerations.
    -Variables that were removed from the model were EIN and name.

    -The final model consists of three layers, containing 25, 12, and 5 nodes and uses the relu and sigmoid activation functions. These parameters were last in the attempts to optimize model to achieve the 75% prediction accuracy rate.
    -Was not able to achieve the target model performance, the closest attempt resulted in a 73% prediction accuracy rate.
    -Steps taken to optimize the model were adjusting the number of layers and nodes and changing to tanh or relu activation functions on different layers.

Summary:
    Overall the results for this prediction model averaged a 73% prediction accuracy rate. Model optimized in an attempt to achieve the target goal more than three times. Could recommend a random forest or decision tree as a simpler model to understand the decision-making process and to determine funding success. 