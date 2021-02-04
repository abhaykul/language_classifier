# Language Classifier

## Train the model:

Training: The data file on which the model gets trained
Output: The name of the file that will contain the trained model as a pickle object.
Type: Type of model training; For decision trees put "dt"; For ada-boosted stumps put "ada"
Testing: The file on which the model is tested for parameter tuning/best tree depth
    
    python3 train.py <Training> <Output> <Type> <Testing>
    
## Test the model:

Model: filename of the model generated by train.py
Data: The datafile for predicting the classifications

    python3 predict.py <Model> <Data>
    
 


    
    
