# Ex03-Univariate-Analysis
AIM:
    To perform univariate analysis on a given data set
ALGORITHM :
    1.start
    2.Read the data from the file
    3..clean the data
     a.remove outliers
     b.fill the null values by using statistical methods or drop the null value coulmn
    3.perform univariate analysis it can be applied only on a single data.
    4.exit
 PROGRAM:
 describe ()code:
 import pandas as pd
df=pd.read_csv("/content/SuperStore.csv")
df.describe()
 output:
 ![image](https://user-images.githubusercontent.com/95408674/191981864-5862b902-8a8a-47a6-9140-dd46de9ce6a3.png)
 info(code):
 df.info()
 output:
 
 ![image](https://user-images.githubusercontent.com/95408674/191982177-09310cb6-030e-4729-9aa7-da32f86d269b.png)
 isnull().sum()
 ![image](https://user-images.githubusercontent.com/95408674/191982532-a6e92ae6-0a72-482d-9e2e-6acd431acacb.png)
 mode method
 ![image](https://user-images.githubusercontent.com/95408674/191984132-7313361c-340f-422f-9506-29b2fdb10098.png)
Box plot:
![image](https://user-images.githubusercontent.com/95408674/191984329-a00b7ea2-b3ad-4cc6-9710-50c164d47836.png)
count plot:
![image](https://user-images.githubusercontent.com/95408674/191984479-9b0df0cc-abc7-4e1e-b808-1f573bc914f4.png)
skew fnction:
![image](https://user-images.githubusercontent.com/95408674/191986002-65e40587-24b0-4792-aa5f-3e91c5d01997.png)
dist plot:
![image](https://user-images.githubusercontent.com/95408674/191985572-5ec70105-db06-4b70-adbb-d946287c5296.png)
hist plot:
![image](https://user-images.githubusercontent.com/95408674/191985708-368bc27b-2ef6-48c9-af9b-a43d9723544b.png)

RESULT:
   Thus we have done the univariate analysis on the given dataset.

 

    
   
 
