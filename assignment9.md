 Part I ­ CBS Football Stats

For this part of the assignment, you will scrape some football stats from the CBS webpage.

    Go to the CBS NFL Stats webpage, located here
    For this example, lets look at the league leaders in touchdowns. Under “PLAYER STATISTICS”,click on the Touchdowns links
    Change the drop down to regular
    Write a script called “football_stats.py” that will load this URL, parse it using BeautiulSoup, and
    output the list of top 20 players, including the player’s position, team and total number oftouchdowns

Part II ­ Stock Data

Another important task in the real world is to download stock data for future analysis. There are many
services that you can get this kind of data from in a convenient format, but many of these services are for
pay. We can do better! For this part of the assignment, we’ll scrape stock data for Apple from NASDAQ.

    To get data about Apple’s stock, we’ll use NASDAQ, located at https://www.nasdaq.com/
    To get Apple Historical Prices, you can go right into this link.
    Write a script called “apple_stock.py” that will load this URL, parse it using BeautifulSoup, and 
    output the close price and date for all the dates shown on the page

Part II ­ NFL  (in case you have trouble with the Apple prices)

In sports betting, the handicappers usually publish the spread of NFL games. Let's say a gambler hired you to retrieve the current spreads from this website 

    Go to the site above to see current spreads.
    Write a script called “nfl_spreads.py” that will load this URL, parse it using BeautifulSoup, and output the 
    favorite, the underdog and the spread of a given game.