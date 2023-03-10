# Automated Trading on NSE using Noiseless Feature Generation and Neural Networks

This is the code for the the following:

1. Generate minute by minute repository of LTP of Nifty 50 stocks
2. Generated noiseless features based on price action and techinical indicators
3. Make Buy/Sell predictions on a real-time basis (50 stocks per minute)
4. Place Buy/Sell orders into Broking platform
5. Generate failure/slippage report and reconcile trade book and order logs
6. P&L Reporting

### Illustrative Graphic to Show AI Agent Trades

![image](https://user-images.githubusercontent.com/17408955/215096619-9e93a170-8a13-4a5c-8d99-b4bc7935b3a2.png)

### Example of AI Agent in Action In a Down Trend

![image](https://user-images.githubusercontent.com/17408955/215096748-fdef45ec-9d4d-4421-9a41-96c93da2a9ce.png)



The code is held in a private repository for purpose of confidentiality - please connect with the author for access

The Buy Algorithm is giving the following results on validation dataset

<img width="367" alt="image" src="https://user-images.githubusercontent.com/17408955/215084722-d5af0bfc-8bf7-4eb9-a12b-117b6c94168a.png">

The Sell Algorithm is giving the following results on the validation dataset

<img width="365" alt="image" src="https://user-images.githubusercontent.com/17408955/215085010-e2b2ebf0-9ba0-4e09-815d-4b8bac6536ac.png">

<p> The model summary of the Sell Algorithm is as follows: </p>

<br>

<img width="413" alt="image" src="https://user-images.githubusercontent.com/17408955/215085244-4fd91026-f599-43bf-a9d7-ed62b8c5eabc.png">


### VALIDATION RESULTS  (BACK TEST of Nifty 50 stocks over 1 year period 01-Apr 2021 to 31-Mar-2022
<p> Assuming every trade to be investment of 100,000 , allowing for a max of 50 positions to be open at any time ( one per stock)</p>

Peak Investment:  -3758900.0 <br>
ROI based on Median Investment =  33.5% <br>
ROI based on Peak Investment =  13.57% <br>
#### XIRR= 48.3%

<img width="288" alt="image" src="https://user-images.githubusercontent.com/17408955/215097136-d12386ee-6ff8-404a-bca6-ea768128775c.png">

<p> Comparable investment is DSP Nifty 50 Equal Weight Index Fund - Direct Plan - Growth <br>
Market return of Buy and Hold strategy 21.02% </p>
