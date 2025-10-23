# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```py
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

marks=[13,45,103,78]
student=['shyam','sudhi','aadhi','mohit']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student Name')
plt.title('Marks vs Student Name')
plt.show()


student=['shyam','sudhi','aadhi','mohit']
attendance=[90,85,73,96]
plt.plot(attendance,student)
plt.xlabel('attendance')
plt.ylabel('Student Name')
plt.title('attendance vs Student Name')
plt.show()
```
<img width="767" height="520" alt="image" src="https://github.com/user-attachments/assets/9ebb2d9d-c1fa-40f8-9ade-66349a2b40c5" />
<img width="765" height="523" alt="image" src="https://github.com/user-attachments/assets/943c1ae0-eec4-491a-8892-0cfde2ade717" />

```py
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.plot(x,y)
plt.scatter(x,y,label='stars',color='r',marker='*')
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

<img width="547" height="819" alt="image" src="https://github.com/user-attachments/assets/e86872bf-eb2f-4e65-94c1-b884c6aafea6" />

```py
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()


feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="434" height="765" alt="image" src="https://github.com/user-attachments/assets/ec4ae85c-ab4e-4c3c-9322-5a321868bb9a" />

```py
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]

plt.fill_between(x, y1, color='red')
plt.fill_between(x, y2, color='blue')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```

<img width="533" height="394" alt="image" src="https://github.com/user-attachments/assets/609bda4f-400f-4815-9614-585714d3fd0c" />

```py
height =[10,20,40,70,27]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="548" height="432" alt="image" src="https://github.com/user-attachments/assets/cd5bd53f-d7da-49b2-865c-4d1933106ad6" />

```py
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=1)
plt.show()
```

<img width="553" height="403" alt="image" src="https://github.com/user-attachments/assets/3b654c0f-a27b-45b4-9d3c-cd02afa31325" />

```py
np.random.seed(0)
Data=np.random.normal(loc=0,scale=1,size=150)
Data
```
<img width="557" height="491" alt="image" src="https://github.com/user-attachments/assets/38f334b7-f2db-4920-9231-7a1da434455c" />

```py
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="566" height="449" alt="image" src="https://github.com/user-attachments/assets/de84aca8-32b4-408c-a5f2-b8c04c25f9a2" />

# Result:
 Thus all the data visualization techniques pf matplotlib has been implemented.
