# Stock-Market-Time Series Forecasting
In this project I used the **Microsoft Stock Market** data which I downloaded in this link:    
link: https://www.kaggle.com/mohamedbakrey/eda-for-microsoft-stock-data-using-ml-algo-acc100/data     

It had no null data.   


![image](https://user-images.githubusercontent.com/67642255/145197907-7f14cc19-b143-4b22-b311-5a2339331ef4.png)


In the following plot you can see the describtion of each feature:    

![image](https://user-images.githubusercontent.com/67642255/145198933-ebeb9d8b-af28-43e5-8be4-12454160cf1b.png)

I considered the **Adj Close** value as target and the remaining values as feature:**['open', 'High', 'Low', 'Close']**
I used 90 % of data as train and the rest of data as test:   
![image](https://user-images.githubusercontent.com/67642255/145199216-93c9a2e6-f36e-4441-9e83-857bd45bfdf3.png)  
I used dufferent methods like:  
- classical analysis,     
- ARIMA,    
- AR,   
- VAR, Exponential Smoothing,  
- LSTM variations,   
- Facebook Prophet   

# LSTM Model

I used an LSTM neural network of keras. 
I trained the network for 100 epochs.
In the following plot you can compare the result of prediction with test values.   

![image](https://user-images.githubusercontent.com/67642255/145199974-e76e5bed-bd9e-4bd5-b687-187617cad402.png)  
# Facebook Prophet
The best result belongs to Facebook Prophet model.   
![image](https://user-images.githubusercontent.com/67642255/219398430-e9c2b452-ea87-4396-8d5d-d9a5fdcb20bb.png)

