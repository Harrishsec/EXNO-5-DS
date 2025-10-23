# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

## Aim:
  To Perform Data Visualization using matplot python library for the given datas.

## EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

## Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

## Coding and Output:
```
NAME:HARRISH P
REG NO: 212224230088
```
```py
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

### Line Plot:

```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()

student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```

<img width="1795" height="719" alt="image" src="https://github.com/user-attachments/assets/ed21bf48-5c20-443b-8944-aa59b6fae6b5" />
<img width="863" height="735" alt="image" src="https://github.com/user-attachments/assets/3b14c1c3-2c0f-48f4-b3e3-79122cc3f02e" />




### Scatter Plot:

```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()

x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```

<img width="908" height="662" alt="Screenshot 2025-10-23 135112" src="https://github.com/user-attachments/assets/feb7627e-4a6f-454a-b552-d3e2df212b3e" />


~~~
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()

~~~

<img width="1051" height="839" alt="image" src="https://github.com/user-attachments/assets/19761e62-732f-43bb-9f60-11e3b76ada49" />



### Pie Chart:

```
import matplotlib.pyplot as plt
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

```

<img width="1366" height="725" alt="image" src="https://github.com/user-attachments/assets/c9186e2f-c813-465a-9771-5c518ddd3794" />

~~~

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

~~~

<img width="1373" height="687" alt="image" src="https://github.com/user-attachments/assets/715d3f59-0a41-4b99-bda5-c5b110ef74e6" />



### Area Chart:

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```

<img width="990" height="802" alt="image" src="https://github.com/user-attachments/assets/9cd82b5f-9f18-4bfb-9f9c-3a5e5efb8942" />




### Bar Chart:

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="988" height="823" alt="image" src="https://github.com/user-attachments/assets/825abed9-0e98-4b65-bf2e-299aca3ab14d" />



### Histogram:

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```


<img width="877" height="634" alt="image" src="https://github.com/user-attachments/assets/5a4530e7-8153-4491-aebb-e1b3e4af93e4" />



### Box Plot:

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```


<img width="956" height="582" alt="image" src="https://github.com/user-attachments/assets/fe50af6a-a3bc-44a0-a88e-1fb81f3c9e8e" />


```
plt.subplots()
plt.boxplot(data)
plt.xlabel('Data')
plt.ylabel('Values')
plt.title('Box Ploat')
```

<img width="1022" height="804" alt="image" src="https://github.com/user-attachments/assets/b2e0c4c1-0f7e-447e-bfb7-dc8b4829cff8" />






## Result:

Thus, all the data visualization techniques of matplotlib has been implemented.
