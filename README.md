from pandas import read_csv
from matplotlib import pyplot
series=read_csv("airline-passengers.csv")
print(series.head())
series.plot()
pyplot.show()![image](https://github.com/user-attachments/assets/fbd492e8-23c3-49d9-b8b8-ff65c164a97a)
series.plot(style='-.')
pyplot.show()
![image](https://github.com/user-attachments/assets/6f357501-b668-4b9b-953a-4a7cbb63b389)
series.hist()
pyplot.show()
![image](https://github.com/user-attachments/assets/1d31f29e-0079-411b-ac39-5886fd4be544)
series.plot(kind='kde')
pyplot.show() 
![Screenshot (11)](https://github.com/user-attachments/assets/f3ac3fd7-0336-4ac2-99ea-89fb501b0dff)

