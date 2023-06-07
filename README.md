# portfolioDoctor

According to several sources, year 2022 saw a record number of first-time investors in stock markets. A good portion of Gen-Z is beginning to have surplus, investible savings. Besides this data - which may be real or cooked up ![Image](https://user-images.githubusercontent.com/20066864/243864065-292f45a0-8d9f-4091-963b-ec8aee2791c9.png) - one can feel that discussions in many social circles are beginning to involve "stock tips" or innocent brags of gains from Apple/Netflix/Tesla, etc etc. Over time, question is certain to come up:

### Is DIY investing worth it? 

Again, data has shown that most professional fund managers do worse than the index. Yet, pride, over confidence or plain beginner's luck, makes many people invest on their own. For this, just as you do a routine doctor's check-up for physical health, your portfolio too needs a regular **health check-up**.

### My broker / bank sends me my portfolio performance reports anyway! Why this?

... because

1. The reports are wrong! Alright - this may be a hard pill to swallow, but TWR (time weighted return) is deemed to be the industry standard for portfolio performance. This method skips timing of investments, which is a crucial factor in performance. Duh!  ![Image](https://user-images.githubusercontent.com/20066864/243864329-9cc0cc55-bd70-4fc0-bd2d-0f714a5a063f.png)
2. Even if the report shows MWR (money weighted returns) or IRR, the evaluation is still logically wrong because - changes to cash as well as returns from Cash are not accounted for. And, most importantly, a real **comparative analysis against index** is missing from such reports. 
3. Their incentives are against you. Brokers earn commissions with each trade. So, they will **NEVER** tell you to quit trading and invest in a boring, low fee index fund. 

For above reasons (and more), this project is launched. 

> Please note that this is not a portfolio tracker. There are far too many portals and applications that exist already. [GetQuin](getquin.com), [Sharesight](https://www.sharesight.com), [Seeking Alpha](https://seekingalpha.com), to name a few, and your own broker's web portal!  

Pictorially, the difference between an "off the shelf" portfolio tracker and "Portfolio Doctor" is shown below. 


![Image](https://user-images.githubusercontent.com/20066864/243858729-5bbe9e64-e845-442c-8245-cb283704abda.png)

- Red line: classic portfolio value tracker. Note that Buy and Sell trades cause the portfolio value to change. 
- Blue line: this is "**Cash-aware**" portfolio tracking. Each BUY trade simulates a withdrawal from Cash. Corresponding Cash amount would stop earning interest, and would be invested. Also, as this cash was available at hand (it is unlikely that the investor really needed it to pay rent or food), it is factored into the initial investment size of portfolio. Similarly, each SELL trade would cause money to flow into Cash, as opposed to portfolio's value dropping as seen in red line. This amount would also earn interest according to a reference rate of money market liquid fund. 

> Thus, a 'tweaked' calculation method offers a better, more real-life way to assess portfolio performance. It also makes benchmarking against index more accurate and realistic. As equities should be invested with a time horizon of at least 3-5 years, practically it is fair to assume that Cash dips and rises from BUY/SELL trades are in/out of a separate Cash account earmarked for investing, rather than a regular cash account. This Cash account is treated as a part of investment.

With benchmarking correctly done, the "Doctor" can now answer many questions and run several what-if scenarios that offer useful insights to the investor.


![Image](https://user-images.githubusercontent.com/20066864/243866423-378681d8-fa5b-4a51-8afd-931c68faca28.png)