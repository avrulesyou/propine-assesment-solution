propine-assesment-solution

Working Process
After running the code it gives a choice to select one of these:
1. Given no parameters, return the latest portfolio value per token in USD
2. Given a token, return the latest portfolio value for that token in USD
3. Given a date, return the portfolio value per token in USD on that date
4. Given a date and a token, return the portfolio value of that token in USD on that date

Input Parameters 
include Date in format 
Date must be format 21 Sep 2022 00:00:00 GMT OR 21 Sep 2023
note:For BTC enter date after 2009,For ETH enter date after 2015,for XRP enter date after 2012.
                                
include Token in Format
BTC/ETH/XRP

It accordingly calculates the current USD value for portfolio for tokens BTC, ETH, XRP
The Total value of token is stored in BTCsum, ETHsum, XRPsum respectively 
Adding for deposit and substracting for withdrawal

Using API min-api.cryptocompare.com we find USD value of given token on the given date
which is multiplied to sum of token
