# Module-Challenge-12

## Technologies


The Application has specific technologies that will be needed to run properly.


**Languages Required:** *Python*

**Libraries Required:** *Pandas, PathLib, sklearn, numpy, imblearn*

Before running the application the following Libraries will need to be imported:

```python
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix,classification_report
from sklearn.metrics import accuracy_score
from imblearn.metrics import classification_report_imbalanced
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from imblearn.over_sampling import RandomOverSampler
```


Further details denoting requirements and verions are available in the requirements file.            

[Requirements](./requirements.txt)


---

## Installation Guide

This app will not work without the proper technologies listed above.  To ensure you have the applicable tools please install the requirements for the Credit Risk Resampling Application using the text file in the Module-Challenge-12 folder as follows:

In The Terminal Run:

```python

pip install -r requirements.txt

```


---

## Usage



### **For Coding and User Purposes:** 

The application is built to provide analysis around Healthy and Risky Loans.

1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model
3. Predict a Logistic Regression Model with Resampled Training Data¶

---

## Contributors

Tracy Davis <TracyMDavis88@gmail.com>

[Tracy Davis LinkedIn](https://www.linkedin.com/in/tracy-davis-mba-ma-2940a232/)

---

## License

MIT License

Copyright (c) [2022] [Tracy Davis]

