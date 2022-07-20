# A Monte Carlo Projection for a Financial Portfolio
----
## About this Software
* A Monte Carlo simulation utilizes a technique of randomly selecting data points using the probability distribution of historical data in order to predict the future. 
* In this application, stock and bond performance was analyzed for the previous 3 years and was used to project a financial portfolio over the course of the next 30 years and 10 years respectively.
* The client in this example had diversified the majority of his holdings into stocks ("SPY") and bonds ("AGG") with a higher proportion of the latter. We wanted to take a look at what weights would be most beneficial for his portfolio over the long term using a Monte Carlo method. 
* The Monte Carlo method gave us 95% upper and lower confidence intervals for our portfolio projection based on the training set of the previous three years of market data.
* In the future I would adjust this application to train the data for an equal amount of time to the projection. So if I was forecasting 10 years into the future, I would use the probability distribution of the previous 10 years of market data. I believe that longer projections require more training data than the 3 years that was used in this application. 

## Usage
* In order to run this application, users must sign up for the Alpaca Markets API and will need to store their public api key, and their secret api key in a local environment file (.env).
* The Alpaca API is used to fetch historical and current stock and bond data for the application.  
* Visit [Alpaca's Website](https://alpaca.markets/) to learn how to gain authentication to use the Alpaca API.