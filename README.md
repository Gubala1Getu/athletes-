**#athletes#**
**#Data cleaning and data visualization project**
Repository creating portfolio of data cleaning project completed by me for self learning presented in the form of Excel
**##Olympics 2024 dataset**
The 2024 Summer Olympics, officially termed the Games of the XXXIII Olympiad and branded as Paris 2024, unfolded from July 26 to August 11, 2024, in France.
the dataset were composed of 11115 records. 
the dataset were downlouded at kaggle website(https://www.kaggle.com/datasets/willianoliveiragibin/olympics-2024)
**Data cleaning cleaning**
the dataset were checked to remove duplicate, unfortunatly there were no duplicat at all.
**countif**
the countif function were performed to check number of female, male participant, invalid measurment weight "0", height "0"
countif(M2:M11116,"0") to check 0 value for height which was found to be 6.032
countif(N:N11116,"0") to check 0 value for weight which was found to be 10,783
**len**
len function was performed to check number of characters reccorded under P colmun (event), after len(P2) performed the result filled to all P2 to P11116 cells then sorted from smallest to largest the minimium character were 7, sorted from largest  to smallest the maximium character were 225.
**Left ()**
left (P2, 7) were performed to extract the seven left most character of Events colmun.
**right()**
right(P2, 7) were performed to extract the seven right most character of Events colmun.
**concatenate()**
concatenate(W2, Y2) were performed to concatenate the seven right most character of Events colmun and the seven left most character of Events colmun.
**filter**
were performed to extract Ethiopian athelets from the dataset
**Data validation**
Data validation were performed to show invalidit of giving 0 value for height and the invalid data circled. 
**Data visualization**
Based on the nature of the data pie chart and bar char were performed.
