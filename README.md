# Ex03-Univariate-Analysis

Aim:
To read the given data and perform the univariate analysis with different types of plots.

Explanation:
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

Algorithm:
Step1:
Read the given data.

Step2:
Get the information about the data.

Step3:
Remove the null values from the data.

Step4:
Mention the datatypes from the data.

Step5:
Count the values from the data.

.Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

Program:
DEVELOPED BY : VAISHNAVI.S

REGISTER NO :212222230165

~~~py
import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()
df.info()
df.describe()
df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x='Postal Code',data=df)
~~~
Output:
Dataset:

![v1](https://user-images.githubusercontent.com/118541897/228145053-709f1b77-e706-446a-86ed-56348210d924.png)

Head:

![v2](https://user-images.githubusercontent.com/118541897/228145209-d44d551f-4c80-4e40-ba5e-c705ebb65995.png)

Info:

![v3](https://user-images.githubusercontent.com/118541897/228145282-68e67bea-02da-4b3b-80dd-fd9a02179d72.png)

Describe:

![v4](https://user-images.githubusercontent.com/118541897/228145515-c8b6557f-b370-4b56-9ffb-5315208309f6.png)

Isnull:

![v5](https://user-images.githubusercontent.com/118541897/228145591-4f0449d3-320e-41fd-bc08-0d843ea32d67.png)

dtypes:

![v6](https://user-images.githubusercontent.com/118541897/228145657-394f5e73-9248-4650-ab99-708d59957c43.png)

Valuecount:

![v7](https://user-images.githubusercontent.com/118541897/228145795-1d627a21-1b92-4713-abd1-f2476b40bbec.png)

Boxplot:











