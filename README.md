# Efficient  and  Effective  Methods  for  Predicting Stock Market Prices
The paper detailing our experiments and results can be found within the "paper" folder, or <a href="/paper/AI_Paper.pdf" class="image fit">here</a> for quick access.

## Requirements
To install and make sure you have all requirements necessary to run our code, you can run `pip install -r requirements.txt` from the root directory to verify necessary packages and install missing ones.


## Brief Instructions
The appendix of the paper has been copied below with instructions on how to run our code:

## Decision Tree
After opening “Decision Tree.ipynb", you can proceedto run every cell in order. Any cell directly below a textin bold red font may be skipped as they are examples or code that take an incredibly long time to run and areinsignificant to the actual experiment/result. If neitherthe code or the dataset has been modified, you should be able to run all the other cells quickly (except for twocells that create the decision trees which takes a littlelonger than instantaneous). You should get the exact same results as we did, as there were no instances ofusing any randomness in the experiment, includingsplitting the dataset and creating the decision tree.

## LSTM
Similar to the Decision Tree, you can proceed to runevery cell in order in “LSTM.ipynb", however since LSTM training does not take as long as Decision Tree, there is no need to skip over any blocks. Also unlike the decision tree algorithm, LSTM does incur some randomness in training. This means the results maynot be identical to the ones presented, however theyshould remain relatively similar.

## HMM
As with the Decision Tree and the LSTM, you can also run every cell in order in “HMM.ipynb", but closing_and_middle_price_in_range will take some time to run. Like the Decision Tree, you should be able to get the same results as there is no randomness in fitting the model. Thus, if you use the same training set, the data should have the same result.
