from pandas import read_csv
from matplotlib import pyplot
series=read_csv("airline-passengers.csv")
print(series.head())
series.plot()
pyplot.show()
![Screenshot (8)](https://github.com/user-attachments/assets/63c106c6-211c-4e20-9d73-baaca0527d79)

series.plot(style='-.')
pyplot.show()
![Screenshot (9)](https://github.com/user-attachments/assets/7352efea-6dec-4728-a8b7-9f3a8a16bfe6)
series.hist()
pyplot.show()
![Screenshot (10)](https://github.com/user-attachments/assets/92a0cdb2-d40f-4895-9465-87a8e93bb7bf)
series.plot(kind='kde')
pyplot.show() 
![Screenshot (11)](https://github.com/user-attachments/assets/f3ac3fd7-0336-4ac2-99ea-89fb501b0dff)
