# Efficient  and  Effective  Methods  for  Pre-dicting Stock Market Prices
The paper detailing our experiments and results can be found within the "paper" folder, or <a href="/paper/AI_Paper.pdf" class="image fit">here</a> for quick access.

The appendix of the paper has been copied below with instructions on how to run our code:

## Decision Tree
After opening “Decision Tree.ipynb", you can proceedto run every cell in order. Any cell directly below a textin bold red font may be skipped as they are examplesor code that take an incredibly long time to run and areinsignificant to the actual experiment/result. If neitherthe code or the dataset has been modified, you shouldbe able to run all the other cells quickly (except for twocells that create the decision trees which takes a littlelonger than instantaneous). You should get the exactsame results as we did, as there were no instances ofusing any randomness in the experiment, includingsplitting the dataset and creating the decision tree.

## LSTM
Similar to the Decision Tree, you can proceed to runevery cell in order in “LSTM.ipynb", however sinceLSTM training does not take as long as Decision Tree,there is no need to skip over any blocks. Also unlikethe decision tree algorithm, LSTM does incur somerandomness in training. This means the results maynot be identical to the ones presented, however theyshould remain relatively similar.

## HMM
As with the Decision Tree and the LSTM, you canalso run every cell in order in “HMM.ipynb", but clos-ing_and_middle_price_in_range will take some time torun. Like the Decision Tree, you should be able to getthe same results as there is no randomness in fittingthe model. Thus, if you use the same training set, thedata should have the same result.
