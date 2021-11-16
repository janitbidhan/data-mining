# Credit-Risk Scoring for Loan Approvals

Develop predictive models that can determine someone’s credit risk 0 - high risk, 1-low risk .

> We need to develop predictive models that can determine given a particular individual whether their credit risk is high denoted by 0 or low denoted by 1.  As such, the goal is to develop the best binary classification model.


#How to Run the code
The code here is to be run in Jupiter Notebook
## Installation
[Installing Jupyter Notebook](https://test-jupyter.readthedocs.io/en/latest/install.html)

## Running Jupyter Notebook
```bash
jupyter notebook
```


> There are 2 IPYNB files i.e a notebook document created in Jupyter Notebook.
> 
>For Analysing of the algorithm and various other parameters
> >HW2_Janit_Bidhan-Analysis.ipynb 
> 
> For actual prediction of labels for the test file
> >HW2_Janit_Bidhan.ipynb 
> 

> ####Change the input data file path or add the files to the same folder for testing i.e. Training and Test Data files Paths

```python
# Reading training Data in the HW2_Janit_Bidhan-Analysis.ipynb
trainingData=readTrainfile("credit_train.csv")
# Reading data files in the HW2_Janit_Bidhan.ipynb 
# Reading training Data
trainingData=readTrainfile("credit_train.csv")
#Reading Test File
testingData=readtestfile("credit_test.csv")
```
