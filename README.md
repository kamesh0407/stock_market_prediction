# stock-prediction Using Machine Learning
Stock price analysis has been a critical area of research and is one of the top applications of machine
Here, we used an LSTM network to train your model with Google stocks data

What is the Stock Market?

A stock market is a public market where you can buy and sell shares for publicly listed companies. 
The stocks, also known as equities, represent ownership in the company.
The stock exchange is the mediator that allows the buying and selling of shares. 

Importance of Stock Market

1)Stock markets help companies to raise capital.
2)It helps generate personal wealth.
3)Stock markets serve as an indicator of the state of the economy.
4)It is a widely used source for people to invest money in companies with high growth potential.

LONG SHORT TERM MEMORY NETWORK:
LTSMs are a type of Recurrent Neural Network for learning long-term dependencies. 
It is commonly used for processing and predicting time-series data. 

Three steps in LSTM:
a)The first step in LSTM is to decide which information to be omitted from the cell in that particular time step. 
It is decided with the help of a sigmoid function.
It looks at the previous state (ht-1) and the current input xt and computes the function

b)There are two functions in the second layer. The first is the sigmoid function, and the second is the tanh function
The sigmoid function decides which values to let through (0 or 1). The tanh function gives the weightage to the values passed, deciding their level of importance from -1 to 1.

c)The third step is to decide what will be the final output. First, you need to run a sigmoid layer which determines what parts of the cell state make it to the output
Then, you must put the cell state through the tanh function to push the values between -1 and 1 and multiply it by the output of the sigmoid gate.

CODES IN DIFFERENT PLATFORMS:
It tooks nearly 48seconds to 58 seconds to run single keras model files in Jupyter n0tebook
But in OPENVINO it took 135 milliseconds to 141 milliseconds to run it where this keras model consist of 100 files to run it and make to fit for the model.
![image](https://user-images.githubusercontent.com/105495867/225071699-5ec37228-52c1-4280-ab0f-9202d2b5ab42.png)
the above image is in openVINO notebook
![image](https://user-images.githubusercontent.com/105495867/225222368-8dacf339-445f-4b2c-8404-53a0526ef6ca.png)

the above image is in local machine's notebook

