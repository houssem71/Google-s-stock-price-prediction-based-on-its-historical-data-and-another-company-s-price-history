# Google-s-stock-price-prediction-based-on-its-historical-data-and-another-company-s-price-history
In this project, I carried out an analysis of the time series which represents the price of the action of Google, after a work of exploration and reshaping of data,
I appealed to another database which includes another company's stock price to form another indicator to predict Google's stock price.
For this project, we used an advanced deep learning algorithm which is composed of 4 LSTM architectures, each of which is formed by 50 neurons. 
Following the modeling, we were able to do the prediction test over the period from 03/01/2017 to 31/01/2017 and we obtained the curve which compares the real value of the action over this period and the value predicted by our model. 
The major finding for this project is the fact that the prediction quality of the prediction value greatly depends on the introduced database of the other company.
Other terms, the more the value of the action of the other company is corrolated to that of Google, the better the result. 
Moreover, in case of the good choice of the second database, we will have a smooth curve at the end and which follows the same trend as the real value of the action of Google. 
The results obtained can be improved by: 
1- increasing the number of LSTM architects used 
2- The number of neurons per architecture 
3-by increasing the timestep which is right now equal to 50
