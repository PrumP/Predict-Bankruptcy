# Predict-Bankruptcy
*The dataset obtained from http://www.scriptedin.com/*

### Columns in data set
1.  SALES: total sales
2.  ROCE: profit before tax=capital employed (%)
3.	FFTL: funds flow (earnings before interest, tax & depreciation)=total liabilities
4.	GEAR: (current liabilities + long-term debt)=total assets
5.	CLTA: current liabilities=total assets Liquidity
6.	CACL: current assets=current liabilities
7.	QACL: (current assets – stock)=current liabilities
8.	WCTA: (current assets – current liabilities)=total assets         
9.  LAG: number of days between account year end and the date the annual report and accounts were filed at company registry.
10.  AGE: number of years the company has been operating since incorporation date.
11. CHAUD: coded 1 if changed auditor in previous three years, 0 otherwise
12. BIG6: coded 1 if company auditor is a Big6 auditor, 0 otherwise
13. The target variable is FAIL, either = 1 or 0. 

## Logistic Regression Model

The logistic regression model from scikit-learn is used in this problem. Inorder to improve model accuracy;

1.  Feature Scaling
2.  Hyperparameter Tuning 

used for data preprocessing and model selection respectively.

Accuracy of initial simple model is improved from 0.71 to 0.86.

 

