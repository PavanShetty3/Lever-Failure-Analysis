# Acute Liver Failure Patients Analysis
Acute livrt failure is loss of liver function that occurs rapidly, usually for a person who has no pre existing liver disease.The JPAC centre for Health Diagnosis and control has conducted nationwide surveys of Indian adults from 1990. The centre had collected wide variety of health information through different modes. This dataset has information of 8785 adults 20 years of age or older from 2008-2009 and 2014-205 surveys.

The dataset has been downloaded from Kaggle website. The link is :
https://www.kaggle.com/rahul121/acute-liver-failure

The steps done in this analysis are as follows:
1) Data collectiom
2) Data analysis
3) Data visualization
4) Data cleaning
5) Algorithm selection
6) Prediction
7) Saving the model

### Important libraries:
```
import pandas as pd
import seaborn as sb
from matplotlib.pyplot import scatter as sm
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split as tts
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import confusion_matrix

```

### 1) Data Collection
data=pd.read_csv("C:\\Users\\Pavan R Shetty\\Desktop\\Project\\Acute Liver Failure.csv")

### 2) Data Analysis


data                    #This displays the entire dataset


