Alphabet Soup Final Report

Overview:
The purpose of this analysis was to create a machine learning model that can predict whether applicants will be successful if funded by Alphabet Soup.


Results:

Data Preprocessing:

The variable that is the target is the column 'IS_SUCCESSFUL'
The variable that is the features are the rest of the columns in the data.
I removed both the EIN and the Name column in this data as they are neither targets nor features for this analysis.

Compiling, Training and Evaluating the Model:

There are 3 layers, 2 activation functions and 1 neuron because that is what I had time to test.
I was not able to achieve the target model performance of greater than 75%.
I changed the layer amount, binning counts and nodes in attempts to increase model performance.

Summary:

This current model aquired an accuracy of 73% with a loss of 56%.

I do believe there could be other models that could also be used to solve this classification problem depending on their base structure and how it would optimize the information in this dataset.