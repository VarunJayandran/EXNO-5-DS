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
 NAME: VARUN JC
 REG NO: 212224240179

 ```
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
 Line Plot:
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
<img width="833" height="527" alt="Screenshot 2025-10-27 102818" src="https://github.com/user-attachments/assets/c2c84b5c-b268-4d45-9566-9b7014fd1d08" />

<img width="835" height="546" alt="Screenshot 2025-10-27 102825" src="https://github.com/user-attachments/assets/d013ac5c-cf88-4f52-93cb-6e12d345d246" />


## Scatter Plot:
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
<img width="797" height="513" alt="Screenshot 2025-10-27 102835" src="https://github.com/user-attachments/assets/43a2862d-c8ea-409a-afc6-c6b04504f077" />


<img width="835" height="566" alt="Screenshot 2025-10-27 102846" src="https://github.com/user-attachments/assets/266728a7-998a-4a6d-b8bf-a40c6f7cfc36" />



 ## Pie Chart:
 ```
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
<img width="720" height="496" alt="Screenshot 2025-10-27 102916" src="https://github.com/user-attachments/assets/959aa57f-14a8-4c14-badf-e95b47e3f049" />


<img width="653" height="503" alt="Screenshot 2025-10-27 102927" src="https://github.com/user-attachments/assets/e94d78ef-7904-437c-a844-79fcbeedeca0" />




## Area Chart:
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

<img width="810" height="515" alt="Screenshot 2025-10-27 102935" src="https://github.com/user-attachments/assets/d0318603-ed08-4b59-9e58-6cd8ed77edaa" />


## Bar Chart:
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

<img width="785" height="580" alt="Screenshot 2025-10-27 102941" src="https://github.com/user-attachments/assets/b8b81237-a1ef-4b37-90d3-7acff776ab18" />



 ## Histogram:
 ```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```
<img width="769" height="510" alt="Screenshot 2025-10-27 102948" src="https://github.com/user-attachments/assets/a8a68302-43de-4142-9773-c1f2995bb0e7" />


 ## Box Plot:
 ```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```

<img width="779" height="447" alt="Screenshot 2025-10-27 102955" src="https://github.com/user-attachments/assets/426c73cf-115a-4092-892d-74358bc7d392" />


```
  fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')

```
<img width="841" height="542" alt="Screenshot 2025-10-27 103009" src="https://github.com/user-attachments/assets/9ecfef4f-c5e7-4f3f-a7dd-604f9bfc91cb" />




# Result:

 Thus, all the data visualization techniques of matplotlib has been implemented.
