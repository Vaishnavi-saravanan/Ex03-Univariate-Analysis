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

```py
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
```
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

![v8](https://user-images.githubusercontent.com/118541897/229687932-b95989bf-7fc8-4af8-a551-9ac299c1be92.png)

countplot:

![v9](https://user-images.githubusercontent.com/118541897/229688019-3a4080d9-002d-46f1-8a8e-a3ddadc44543.png)

Discription Plot:

![v10](https://user-images.githubusercontent.com/118541897/229688045-8da0a8ca-bc85-41a8-b4b2-4299bc1f7ecb.png)

Histogram plot:

![v11](https://user-images.githubusercontent.com/118541897/229688054-85b1f271-bbc5-448d-b63e-ec3b2e1611b9.png)

DIABETES.CSV:
Data set:
![v12](https://user-images.githubusercontent.com/118541897/229688981-5a44422d-298a-441b-8f53-d6e5bf439a34.png)
Head:
![v13](https://user-images.githubusercontent.com/118541897/229688997-f10ae4c2-5097-4211-bd44-a61af262206c.jpg)

![v14](https://user-images.githubusercontent.com/118541897/229689011-5aa268a1-b496-4278-9775-4e0e2a6ddcff.jpg)

![v15](https://user-images.githubusercontent.com/118541897/229689027-c59699d2-3e18-4d2b-aebf-4c76e07dff97.jpg)

![v16](https://user-images.githubusercontent.com/118541897/229689039-5a167574-bbc8-4823-81a3-d2b56684b241.jpg)

![v17](https://user-images.githubusercontent.com/118541897/229689047-6d68e1af-6028-43a5-add2-26b0cae861e6.jpg)

![v19](https://user-images.githubusercontent.com/118541897/229689066-93194838-8f76-44a9-87ef-ac16599a6b67.jpg)

![v20](https://user-images.githubusercontent.com/118541897/229689083-9635aab2-8d8e-4b89-9160-570ca0c3d87b.jpg)

![v21](https://user-images.githubusercontent.com/118541897/229689101-d99da6da-c78d-422c-81c8-af5bb14ab2db.jpg)

![v22](https://user-images.githubusercontent.com/118541897/229689245-4dfa7e87-ee6d-41b1-a3eb-4cdf8c0c7a2d.jpg)

![v23](https://user-images.githubusercontent.com/118541897/229689164-2dc2f3f9-7b1c-4eb4-9fad-caea43427939.jpg)














