## Lab Session-7 : The financial markets do not punishes security breaches for a short-term

#### Objectives: Redesign the visual created in lab session 3.
#### Date: 04-Nov-2017
#### Tableau Link: https://public.tableau.com/profile/nikhil.kaushik#!/vizhome/Book_12_0/Dashboard_1?publish=yes

#### Steps
* Critique your visualization
* Develop a roadmap for improvement
* Improve your visualization
* Explain how you have improved your visualization


#### Purpose of Lab-3:
Develop a persuasive visualization for data breaches and its impact using stock prices as a parameter. This required data wrangling to read JSON symbols from Yahoo Query Tool to extract and clean stock price data of various companies from Yahoo Finance. 

**Technology Used:** Python in Jupyter notebook to extract stock data from Yahoo Finance. This extraction is done from JSON file and then based on Ticker values the stock prices for 40+ companies were picked.
In this Lab, we made use of Fuzzy Wuzzy giving more insights of how we can do string matching using it.
***

**Claim:** The financial markets does not punish security breaches

**Warrant:** The stock prices is one of the parameter to judge a companies performance in the financial market.  The positive change in stock price indicates that even after the data breach, company did not have to suffer much in terms of stock price.

**Backing:**  The data is used from Yahoo Finance to get the stock prices. Link of Yahoo Finance: https://finance.yahoo.com/quote/ADBE/

**Reservations:** The stock price we have taken here is average stock price for the year. We don’t know what was the immediate impact on the stock right after the breach. Also, the claim is based on just the stock prices. May be the market value of the company might have decreased due to the breach.
This makes it difficult to conclude the claim with the present data.

***
### Road map with future features/enhancements/features (For Lab-3):
***
**1.**  The visual created in Lab-3 shows data for one particular company. This particular company could be an outlier, in turn can prove this visual a 'deceptive' one.

**Improvement:** Add more details in the caption regarding why the particular company is chosen.

**2.** The references are missing in the visual. Refrences add more value to the product.

**Improvement:** Add references in the caption.


**3.** The analysis is based just on the basis of stock prices and this could again be not a sufficient parameter to make the claim.

**Improvement:** More parameters could be addded to this visualization. For instance, security breach could affect the market valuation of the company. So, market valuation could be used as one of the parameters too.

**4.** The visual doesn't provide any data about how the overall market reacted in that particular year.

**Improvement:** Adding information about how the overall market was reacting in that particular year also gives some sense of support to the claim. There could be a case when the drop in the stock price is due to the overall market crash and not because of the security breach. If the market reaction is mentioned in the visual, the user doesn't have to seacrch for this information in case of doubt.

**5** The reaction of security breach could affect different companies differently. The companies which are more data centric such as banks/financial firms would react highly to breaches.

**Improvement:** The analysis could be based on different segments of companies. Segmenting data based on the category could help in resolving the issue. Financial firms may react to breaches completely differently when compared to IT companies.

**6** The graph lacks important information like overall number of incident that took place in that year.

**Improvement:** Add the information reagarding number of breaches taking place in 2013 to give users a better insight of data.

**7** The visual lacks important information like 'Total number of records stolen in Adobe'.

**Improvement:** Add the information reagarding 'Total number of records stolen in Adobe' in 2013 to give users a better insight of data. There might be a scenario where the number of records stolen are comparitively less and therefore it didn't affect Adobe's stock prices.

***
### Take aways from Lab-7 Session are:
**Perception:**

* Adding information like 'Total number of breaches' and 'Total number of records stolen' can give users a better perception of data. Adding the absolute value to the visual could be of great importance in certain scenarios, helping users in understanding the actaul background of the scenario. This data when combined with comprehensive data helps users in taking a better decision.

**Comprehension:** 

* This data is more like averages or change in prices for intance. This is the data which shows a change. In this visual the change in the stock price is the comprehensive data. This type of data helps users in understanding due to certain event how the data changed. For instance in this visualization, due to the event of 'breach' how the stock prices were affected over a certain period of time. 

**Projection**

* This data is more about creating a "what-if analysis". This type of data represent a trend or a pattern in the data. Using this we try to project how the values could change according to the scenario. For instance in this particular visual, if we add a trend line showing the 'number of records stolen' vs 'the number of breaches/hacks' this would be an interesting trend to see. This will help users to estimate or project what could be the possible values in future. 
Although in this particular case we lack data to show any trend, so we are not including this section in the visual.

The above mentioned three types combined with a claim made in a visual helps users in taking a better decision.
