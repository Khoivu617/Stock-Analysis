# Stock-Analysis
Plan for making stock predictions

1. Get reliable data. First is to get historical data from 10-20 years ago for all of the stocks I plan to buy. Right now, those stocks are Apple, Microsoft, Google, Bank of America, Microvision, NIO, YMAB, and maybe more.

Then, I will use APIs (from Yahoo, Google, Robinhood, or other platforms) to get up-to-date market statistics on the stocks I mentioned. There will be a folder in github where it is dedicated to hold new statistics everyday. 

2. The plan is to get those new statistics in form of a CVS or JSON format, do predictions on these statistics, then after the day ends before the next market open I will add these new statistics to the historical data that will be used to train my model. 

Two folders: one called historical_data which will be updated everyday.
The other called new_data which will be used to make predictions, then delete from the new_data folder and add to historical_data. APIs will be used to get a new updated list of stock stats which will be added to this folder. 

3. The model will essentially be updated everyday for a more accurate result. In addition to stock stats, news from sources such as Google news, Yahoo news, reddit news (from wallstreetbets and the likes), and Robinhood news will be used for better predictions. Using web scrape or if those sources have API to get informations, and then use Python libraries for sentimemnt analysis.