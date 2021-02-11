# One Thousand and One...Project Ideas

## Bio/Med-tech

### 1. First aid kit & Medication Tracker (Mobile)

|               |          |
| ------------- |----------|
| Geography     | *RU*     |
| Tags          | *mobile* |


**Functionality:**
1. List all items in a kit
2. Notifications on expiration date
3. Pill reminder

**Additional monetization:**
1. (*) Search&Compare drug prices
2. No limit on notifications


### 2. Medical lootboxes

|               |          |
| ------------- |----------|
| Geography     | *EU, RU* |

Why not to start with some vitamine combos from https://iherb.com?
Or check out: https://transcend.me/products/your-personalized-packets-11


### 3. Cheap lucid dreams mask

|               |          |
| ------------- |----------|
| Geography     | *World* |
| Tags          | *Kickstarter*, *Hardware* |


<img width="467" height="175" src="https://raw.githubusercontent.com/wowinter13/1000_and_1_project_ideas/master/lucid-dreams.png">


**Description**

*(A lucid dream is a type of dream where the dreamer becomes aware that they are dreaming. During a lucid dream, the dreamer may gain some amount of control over the dream characters, narrative, and environment. @Wiki)*

The lucid dreams mask is a type of smart mask, that tracks REM Sleep and causes lucid dreaming using audio or/and visual methods. Actually, there are at least two products currently on the market: Remee and Somni.

Remee's price is \$44.90 and it even **can't track** your eyes to define the REM phase. Somni's price is about **\$200.0**, but the product looks fine – they even added headphones for it. So we need to create a mask that is more functional than a Remee mask, but also is cheaper than a mask by Somni. How could we do it? Let's use heart rate monitors inside our smartwatches! During REM sleep, we can observe an overall increase in blood pressure and heart rate.

**MVP:**

1. Create an app to access and read your sleep data (https://www.appcoda.com/sleep-analysis-healthkit/)
2. Track any unstable heart rate increases and trigger a weak vibration on watches or (*)*send an event to a remote mask*; which now became much comfortable without heavy warm eye-tracking block on it.
3. (*) Create a mask 😃. (hint: check a technology behind the Spring water bottle)


**Why now?**

Because all existing solutions are too expensive or use obsolete technologies to track sleep phases. And the demand is quite stable.


****

## Invest-tech/Fin-tech

### 1. Quasi-broker

|               |             |
| ------------- |-------------|
| Geography     | *EU, RU*    |
|               |             |


### 2. Financial news/ideas/analytics aggregator

|               |             |
| ------------- |-------------|
| Geography     | *World, RU* |
| Tags          | *telegram*  |
|               |             |

**Twitter data sources:**

1. (*RU*) @ArtCapitalTrade, @prime1, @onfleek419, @divalerts, @trader_book_news, @russianmacro, @Trade_The_News

2. (*International*) @barton_options, @DiMartinoBooth, @pat_hennessy, @biancoresearch, @CitronResearch, @profgalloway, @Fxhedgers, @old_but_works, @nntaleb, @muddywatersre, @govttrader, @jessefelder, @ThinkTankCharts

**MVP:**
At this stage, a Telegram/Twitter bot would be enough. For some inspiration, you could check these links: https://t.me/headlines_for_traders, https://t.me/fin_twitt, https://t.me/StockNews100
The only problem – possible news duplications, can be solved using algos such as `Word2vec` or `Doc2vec`.

**Functionality:**
1. A real-time news feed for traders
2. Filters on companies (*tickers*)
3. Filters on data types (*analytics, news, div calendar, etc.*)


### 3. Scouting for business jets

|               |             |
| ------------- |-------------|
| Geography     | *World, US* |
| Tags          | *alternative data*, *API*, *SaaS*  |

Guys from Quandl did this trick.
1. They started tracking for Buffett's jets and watching all flights.
2. After that, they found companies' offices (*from the above cities*), where Berkshire Hathaway had some interest.
3. *Magic.* Sort all given data by flight  quantity and frequency.
4. PROFIT: **Anadarko Petroleum**. Buffett had visited \$OXY a couple of times right before the $10 billion deal was publicly announced.


### 4. ML-darkpools

|               |             |
| ------------- |-------------|
| Geography     | *World, US* |
| Tags          | *alternative data*, *trade matching*  |


**Description**
*(A dark pool is a privately organized financial forum or exchange for trading securities. Dark pools allow institutional investors to trade without exposure until after the trade has been executed and reported. Dark pools are a type of alternative trading system (ATS) that give certain investors the opportunity to place large orders and make trades without publicly revealing their intentions during the search for a buyer or seller. @Investopedia)*

When a trader places an order to buy stocks, the stock exchange matches it with a counter one to sell. ML middleware could split this order into smaller composite parts.
So we reduce the impact of the trade on the market price; optimizing the process of trading for big and complex positions.


**Why now?**
Here we have a strong interest from small/medium-sized funds, which can't use darkpools from such guys as Morgan Stanley or other big banks, but still don't want to move some penny stock prices (or emerging market stocks) simply because of portfolio rebalancing.

### 5. Advanced Backtesting

|               |             |
| ------------- |-------------|
| Geography     | *World, RU* |
| Tags          | *API*, *alternative data*, *SaaS*  |


**Description**

Relatively speaking, that is a strategies' backtesting using data on crises and unexpected stock market crashes.

A platform that rafts your strategy through plenty of simulated crises, industry risk cases and can define some historical risk index for the total portfolio.
Also, we have some space to dream up ideas based on the intersection of value investing and stocks scoring. So we will be able to find out the best companies which can transcend any market difficulties.

**MVP:**

Let's be fair - it is just a simple pseudo stock exchange, that has the functionality to process (ETL) and reply data. Also, it could be a set of pseudo stock exchanges to train arbitrage strategies.
And the funny thing is – that you could find all these *Black Swan Events* or *alternative data* in countless different public sources.


**Why now?**

<img width="372" height="243" src="https://raw.githubusercontent.com/wowinter13/1000_and_1_project_ideas/master/backtesting-1.jpg">

Let's have a look at this chart by Bloomberg. It's a little outdated, but it still looks actual. Every year the hedge-funds and biggest investment banks increase their spendings on technology and **quant strategies development** while cutting spendings on direct trading and front-offices.

In the world of algos and robots, it is getting harder and harder to trade discretionarily.


### 6. Mistaken tickers

|               |             |
| ------------- |-------------|
| Geography     | *US, World* |
| Tags          | *alternative data*, *SaaS*  |


**Description**

1. Markets can stay irrational longer than you can stay solvent. (Keynes, 1930)
2. Apes together strong. (Rise Of The Planet Of The Apes, 2011)

Inefficient markets, combined with Robinhood apes, gift us with plenty of awkward and stupid market situations. One of them is a case when the original stock goes up while some other share with a similar ticker or name also starts to surge.

<img src="https://raw.githubusercontent.com/wowinter13/1000_and_1_project_ideas/master/800-return.gif" min-width="250px" max-width="400px" width="250px" align="right" alt="real money">


**MVP:**

1. Parse all stock tickers and their names (also, do not forget that you could have the same name on different exchanges).
2. Match all similar strings and create a dictionary for them (or create an index, it depends on how deep you plan to analyze the data)
3. Subscribe to real-time market data and track your dictionary keys (*key is a ticker of the original company*)
4. If the ticker swings more wildly in relation to the overall market (*regarding stock's beta*), create an alert (**or buy*).
5. (*or buy) As you understand, you easily could create a day-trading algo to track all market inefficiencies (for example, with Alpaca Markets API or IB API).


**Examples**

1. **\$DUO**: from \$10 to \$130 in 4 hours. 
    **FAANG** is an acronym referring to the stocks of the five most popular American technology companies: Facebook, Amazon, Apple, Netflix, and Google. Actually, there is no ETF's called \$FAANG (*the closest one is called \$XLC*). But new retail investors don't know anything about it. As a result, on 9 June 2020, we had \$DUO shares up nearly 395 percent. Why? Simply because Robinhooders heard everyone is buying FANG stocks and they rushed out and bought **FANG**DD *Network Group*, a Chinese company.

2. **\$GME** soared 60% in a day.

    I'm almost sure that the original \$GME stock was also up 60% or more, but this \$GME is from Australia.

    (In January, during Gamestop (\$GME) short-squeeze, company shares soared by a staggering 7000%)


    <img width="446" height="250" src="https://raw.githubusercontent.com/wowinter13/1000_and_1_project_ideas/master/gme-stock.jpg">

3. Elon signals to use Signal.

    “*Use Signal,*” the Tesla Inc. CEO wrote on Twitter on Jan. 7. And it was referring to the encrypted messaging service...But by the end of the same day, **Signal Advance Inc** (\$SIGL) shares surged up 600%. And you may ask yourself, "What was wrong?". The signal was wrong. A two-word app recommendation from Elon Musk has turned into a massive rally in the shares of **a tiny medical device company** in another case of mistaken identity.

    <img width="413" height="232" src="https://raw.githubusercontent.com/wowinter13/1000_and_1_project_ideas/master/signal.jpeg">


**Why now?**

“*Retail participation is at levels we haven’t seen in 20 years,*” said Benn Eifert, managing partner of QVR Advisors.


### 7. AI Open/Closed Ended Funds

|               |             |
| ------------- |-------------|
| Geography     | *US, RU, World* |





****
## Common

### 1. Vinyl lootboxes (or subscription)

|               |             |
| ------------- |-------------|
| Geography     | *World, RU* |
| Design     | https://dribbble.com/shots/6255851-SQUARE-Interaction-Vol-3 |

**Why now?**

*In 2016, vinyl sales hit a 28-year high – and there’s no slowing it down! Maybe it’s time to restart the business model.*

(Source: https://fortune.com/2016/04/16/vinyl-sales-record-store-day/)
