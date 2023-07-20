<h1>stock-prediction Using Machine Learning</h1>
Stock price analysis has been a critical area of research and is one of the top applications of machine.
So, I focused on building a Time-Efficient and approximate stock predictions, for google stocks with the RNN using LSTM Keras model
The model was trained using Google's stock market data(Date, Open, High, Low, Close, Volume) to enhance its technical proficiency.
The keras model helps to create a model, layer by layer. The dense layer is fully connected layer, so all the neurons in a layer are connected to those in a next layer by using tensorflow as a backend.

<p align="center">
  <img src="![tool-thumbnail-beta-oneapi-logo](https://github.com/kamesh0407/stock_market_prediction/assets/108885723/848144f8-f1c7-4f88-8761-5e266d4fc4ca)" alt=" ">
</p>



The Intel® OneAPI toolkit, Intel® OpenVINO toolkit enables models to be trained in a more efficient way and results in faster training times. ADAM optimization algorithm is used and a MSE loss function is optimized.


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

<h2>Description</h2>

CODES IN DIFFERENT PLATFORMS:

It tooks nearly 48seconds to 58 seconds to run single keras model files in Jupyter n0tebook
But in OPENVINO it took 135 milliseconds to 141 milliseconds to run it where this keras model consist of 100 files to run it and make to fit for the model.
![image](https://user-images.githubusercontent.com/105495867/225071699-5ec37228-52c1-4280-ab0f-9202d2b5ab42.png)
the above image is in openVINO notebook
![image](https://user-images.githubusercontent.com/105495867/225222368-8dacf339-445f-4b2c-8404-53a0526ef6ca.png)

the above image is in local machine's notebook

