<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>INDIVIDUAL PROYECT Nº2</b>
</h1>
 
# <h1 align="center">**`Stock Market`**</h1>

<p align='center'>
<img src="https://raw.githubusercontent.com/GabrielGM93/Individual_Project2/master/Assets/Stockmarket.jpg"  height=200>
<p>

Welcome! On this occasion, I did a job placing myself in the role of a ***Data Analyst***.


### **Context**

The emergence of the COVID-19 pandemic had significant implications on the international financial market, with a marked movement of investments towards technology companies and monetary issuance by governments to help those whose incomes were affected. This led to a hyper-liquidity at a global level and an increase in migration to the US dollar, causing many developing countries to see their debts in dollars become more expensive. Additionally, there is uncertainty regarding the global economic situation and the impact of other geopolitical events. In the financial market, governments and companies can obtain financing while individuals can invest their savings and earn profits.

 
### Rol to develop

The task at hand is to simulate a scenario where a company that wants to invest in the stock market requests a detailed analysis. Since the company has no knowledge of this financial area, they request an explanation of what has happened in this market in recent years (considering positive and negative impacts since the year 2000), investment recommendations (either focused on companies or their sectors), and other complementary information.

Due to the large number of companies in the stock market, the analysis is requested to be limited to companies belonging to the SP500 index ([Standard & Poor's 500 Index]).

Thus, the main objective is to understand the situation of the stock market in the last 23 years based on the aforementioned points, allowing you as a Data Analyst to provide a context of the situation and generate investment recommendations.


## **Proyect**
  
Once the EDA (Exploratory Data Analysis) is carried out, I confirm that there are missing values, outliers, anomalies, and proceed to make a line graph over time for the 11 sectors that make up the S&P500. Our Y-axis shows the Adjusted Close, and a second line chart that shows Volume over time.

2000-2002: The S&P 500 experienced a significant decline due to the dot-com bubble burst and the 9/11 terrorist attacks. The US economy went into recession and the S&P 500 lost about 50% of its value.

2003-2007: The stock market recovered during this period thanks to the accommodative monetary policy of the US Federal Reserve and rising commodity prices. The S&P 500 had strong growth, reaching an all-time high in October 2007.

2008-2009: The stock market experienced another significant decline due to the global financial crisis and the ensuing economic recession. The S&P 500 fell more than 50% from its 2007 peak.

2010-2012: The stock market gradually recovered during this period due to the accommodative monetary policy of the US Federal Reserve and rising corporate earnings. The S&P 500 had sustained growth and surpassed its all-time high in April 2012.

2013-2015: The stock market continued its recovery during this period, driven by low interest rates, rising corporate earnings, and global economic growth. The S&P 500 had steady growth and reached new all-time highs.

2016-2019: The stock market experienced record expansion during this period due to the US tax reform, rising corporate earnings, and global economic growth. The S&P 500 had steady growth and reached new all-time highs.

2020: The stock market experienced a significant decline in March due to the COVID-19 pandemic and the lockdown measures implemented to slow its spread. However, thanks to accommodative monetary policy and fiscal stimulus packages, the stock market quickly recovered, and the S&P 500 closed the year with positive growth.

2021: The stock market continued its recovery during this period due to global economic recovery, low interest rates, and rising corporate earnings. The S&P 500 reached new all-time highs.

<p align='center'>
<img src="https://raw.githubusercontent.com/GabrielGM93/Individual_Project2/master/Assets/AdjClose1.jpg"  height=500>
<p>
  
 Starting in 2021, we can see a sharp drop in the value of stocks due to the pandemic, which ends its decline by 2022. My study will focus on those sectors with positive slopes in their adjusted closing after the second quarter of 2022 (which is where the pandemic-related stock drop ends and sectors start gaining strength again). We will take those sectors with the highest stock values and positive slopes, and we can notice that some of them are: Total Consumer Discretionary, Total Health Care, and Total Industrial.

Once chosen, we will compare them in the Volume chart to identify their investment behavior. Of these three chosen, Consumer Discretionary is the sector that receives the most investments. Now what we are going to do is to study each sector separately, study its percentage variation, try to determine its volatility, and at the same time, we will make a line chart based on time with the Y-axis regarding the adjusted closing on the companies that make up that sector. Then we will apply the same procedure, and we can determine which companies have a higher stock value and continue with a positive slope.

The foundation is that under any variable that can affect the stocks of the S&P500 in general (such as the global financial crisis of 2008, pandemics, wars, inflation), there are certain sectors that remain essential for human development. They receive help from the relevant governments, for example, new legal measures to prevent their fall and provide society with the tools to overcome the problem, thus reducing the investment risk in those sectors.

Within Total Consumer Discretionary, we can see that its percentage variation towards the last quarters is positive, and that the two growing companies with the largest stock values are: "NVR," a company engaged in home construction, and "AZO," an American retailer of aftermarket automotive parts and accessories.

Within Total Health Care, also with a positive percentage difference, we determine that the two best companies in terms of stock value and growth are: "MTD," a multinational manufacturer of scales and analytical instruments, and "REGN," an American biotechnology company.

Finally, in the Total Industrial sector, we have: "GWW," an industrial supply company, and "NOC," an American multinational aerospace and defense technology company.

Through these analyses, we can determine that these six companies are the most feasible when making an investment. We can add to the report the study of the volatility of each company, which we obtain by calculating the standard deviation of the sum of percentage variation over the number of cycles taken.
  
<p>
