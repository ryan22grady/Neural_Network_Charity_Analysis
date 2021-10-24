# Neural_Network_Charity_Analysis

## Purpose
Bek’s come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With my knowledge of machine learning and neural networks, I used the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Results
### Attempt 1
 - Data Processing
    -To clean the data I removed the EIN and NAME columns since they have no value to the model.
    -The varibales being considered for my model are as follows: 'STATUS', 'ASK_AMT', 'IS_SUCCESSFUL', 'APPLICATION_TYPE', 
     'CLASSIFICATION', 'USE_CASE',          'ORGANIZATION', 'INCOME_AMT'. I dropped "USE_CASE_Other","AFFILIATION_Other"       
     columns.
    -My Dependent varible is "IS_SUCCESFUL" since we want to try to predict this with high accuracy.
    -Compiling, Training, and Evaluating the Model Attempt #1

 - 2 Hidden Layers
    -80 neurons (Layer1), 30 neurons(Layer2)
    -Used Relu and Sigmoid Activations Functions since sigmoid is best for binary classifcation problems as this and relu is
    for nonlinear datasets.
    -Removed "USE_CASE_Other","AFFILIATION_Other" columns.

![Screen Shot 2021-10-24 at 4 17 56 PM](https://user-images.githubusercontent.com/84995704/138613379-afa839ba-b89a-4513-8805-365be3079bbd.png)

### Attempt 2

- 3 Hidden Layers
- 80 neurons (Layer1), 30 neurons(Layer2), 15 neurons(Layer3)
- Used Relu and Sigmoid Activations Functions since sigmoid is best for binary classifcation problems as this and relu is for    nonlinear datasets.
- Removed "USE_CASE_Other","AFFILIATION_Other" columns.

![Screen Shot 2021-10-24 at 4 18 29 PM](https://user-images.githubusercontent.com/84995704/138613398-0d3a1761-26cb-4ce1-aebf-243f727db07c.png)

### Attempt 3:

- 3 Hidden Layers
- 80 neurons(Layer1), 35 neurons(Layer2), 10 neurons (Layer3)
- Used Relu and Sigmoid Activations Functions since sigmoid is best for binary classifcation problems as this and relu is for nonlinear datasets.
- 400 Epochs
