# workshop-Multivariate-analysis

Types of Bivariate Analysis:
import pandas as pd

data=pd.read_excel('/content/FlightInformation (1).xlsx')

data.head()

data.dtypes

data.info()

(i) Numerical & Numerical
import seaborn as sns

sns.scatterplot(y=data['Price'],x=data['Total_Stops'],data=data)

(ii) Numerical & Categorical (20 marks)
sns.barplot(y=data['Price'],x=data['Source'],data=data)

Multivariate Analysis (40 marks)
data.corr()

sns.heatmap(data.corr(),annot=True)

## OUTPUT:

![image](https://user-images.githubusercontent.com/84709944/229768094-d7626da4-2fd5-47f5-9c51-d1734c77c331.png)

![image](https://user-images.githubusercontent.com/84709944/229768162-c6a7b803-7a07-43f0-998d-f4f69bea60c5.png)

![image](https://user-images.githubusercontent.com/84709944/229768216-abfcf257-247c-4813-9a51-6139aee84ace.png)

![image](https://user-images.githubusercontent.com/84709944/229768289-d9467805-c50e-487b-8469-8102ee1bb3fd.png)

![image](https://user-images.githubusercontent.com/84709944/229768360-9d3f5286-2737-4ea3-acf0-d75804b42e47.png)

![image](https://user-images.githubusercontent.com/84709944/229768418-fb467e32-eb32-467c-b556-f5e40987653a.png)
