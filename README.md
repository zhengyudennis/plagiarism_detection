# plagiarism detection
In this project, we build NN model for plagiarism detection. The data set includes original text and different types of plagiarism. The longest common subsequence (LCS) and n-gram containment features are extracted from the texts. Then a three-layer NN model is built to identify plagiarism.

## Files
`2_Plagiarism_Feature_Engineering.ipynb`: a jupyter notebook for extracting _LCS_ and _n-gram containment_ feature for the training and test samples. <br/>
`3_Training_a_Model.ipynb`: a jupyter notebook for training _NN_ model. <br/>
`helpers.py`: a list of helper functions such _pre-processing_ the texts. <br/>
`model.py`: A _pytorch NN model_ including forward function.<br/>
`predict.py`: the code to evaluate the model.<br/>
`problem_unittest.py`: the _unit test_ code for ipynb files.<br/>
`train.py`: the code to train the model.<br/>  
