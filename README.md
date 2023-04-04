# workshop-Multivariate-analysis

import pandas as pd

df=pd.read_excel("/content/FlightInformation (1).xlsx")

df.head()

df.dtypes

import seaborn as sns

sns.scatterplot(x=df['Total_Stops'],y=df['Price'],data=df)

sns.barplot(x=df['Source'],y=df['Price'],data=df)

df.corr()


##  OUTPUT
![work 1](https://user-images.githubusercontent.com/120440439/229817629-98bfe62a-6666-4f46-8c63-af8f5c12230a.png)

![work 2](https://user-images.githubusercontent.com/120440439/229817719-00d1497c-2b8a-4ac3-a28e-5e0698d413d7.png)

![work 3](https://user-images.githubusercontent.com/120440439/229817881-b51896d8-3e70-4852-8cb1-e5d9dc53c97b.png)

![work 4](https://user-images.githubusercontent.com/120440439/229817940-26387649-e099-429c-a4cb-822b5af4fda9.png)

![work 5](https://user-images.githubusercontent.com/120440439/229817992-028db3e7-f7b0-4cd5-bd8b-83634e600148.png)
