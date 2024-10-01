# di-hackathon-2-da

Project for the Data Analytics hackathon (Developers Institute) is done by **Manuel Guzmán Kizer** and **Vlad Grinberg**.


In this project we analyzed sales and social media performance of the art oriented online shop.

The data was obtained from the shopify and meta account directly. It contains a lot of interesting field and has a vast time range.

## **Datasets:**

* **Shopify** - each row is a purchased item for each order by date. It also contains billing, item, sale metrics and customer data.
* **Instagram and Facebook** - contains data for each post by date with extensive range of fields including metriks like inmpressions, likes and shares.

## **Results**:

* **sales_analysis.ipynb** - provides extensive analysis of the sales data.
* **instagram_posts_analysis.ipynb** - focuses more on analyzing instagram posts metrics.

## Key Takeaways and Insights

* **Geographic**:

  1. USA makes up **86%** of the net sales. *Suggestion: Focusing our attention on that region is the main priority.*
  2. We also could explore new growth opportunetiesin regions with high **average purchase value (APV)** such as **'United Arab Emirates', 'Switzerland', 'Germany'**. *Suggestion:  Launching marketing campains to raise brand awareness.*
  3. Best performin USA state is **New York** with top 2 amount of orders and high APV. *Suggestion: This region should be our priority for marketing.*
  4. There are also interesing states like **'Rhode Island', 'South Carolina' and 'Kentucky'** that have sustainable APV but low orders amount. *Suggestion: We should focus on raising avareness of our brand there.*
  5. **California, Taxes and Florida** are exeptionaly performing in terms of orders amount but realy lacks in APV.
     *Suggestion: Apropriate strategy could be to encourage them to spend more money by offer special deals on high prices art pieces.*
* **Customers**:

  1. **Returning** customers' APV is significantly higher that of **First-time** ones. So we shound inspire clients to return for another purchace.  *Suggestion: We see one approch already implemented right on their landing page. They mention that painting is a great gift which is a great strategy. Because you probably need only one painting for yourself but you could purchase it as a gift and may spend even more money. We could explore ways to expand on this idea even further.*
  2. Returning customers make up **40%** of the total.   *Suggestion: It already quite impressive but we shold push it furhter by introducing some kind of membership program or special deals on gift collections.*
  3. We see that at the end of **2020** there is a huge wave of new customers and also some activity from returning ones.
     However, in **2021** there the first-time clients portion is significantly lower. And regular customers even exceed them in **2022** with few unusual spikes.
     At the end of **2022** the picture is even more pronounced with majority of purchases coming from returning clients.
     In **2023** we again abserve huge activity from new comers.
* **Products**:

  1. By far most popular type is **Mini** and **Gift Collection** and their change in price significantly impacts order amount and there for Net Sales. As majority of customers buy paintings from **Mini** series, price increase affects Net Sales jurasticly especially **First-time** client.   *Suggestion: We should change price very carefully and consciously by small increments and may be offer small discount for the new comers.
     We see that slow price increase of the **Gift Collection** pieces led to reduced impact on sales. Also regular discounts keep customers interested.*
  2. Now we can see that negative sales trend is partially asociated with the price inreace of all products. And we can count price drops as one of the reasons for the increase in sales in the last quater of each year.
  3. We observed that price change has statisticaly significant impact on **Mini** and **Gift collection** types. And we also can see that it affects returning customers more and they have same rate for both categories. For first-timers effect is a bit less tangible with mini being slightly larger. So we can estimate what effect our new price could create and tailor supply acordingly.
* **Referring Channels**:

  1. **Facebook** plays a huge role in attracting new clients to the store.  *Suggestion: It would be a great idea to focus our marketing efforts on this channel*
  2. Next valuable channel is **direct**. It could signify that customer came with clear intentions. It also hight APV.
     *Suggestion: We could expand this channel by launching some kind of refferal program for customers or give bonuces for sharing their experience on social media.*
* **Facebook posts**:

  1. There are few posts that are became viral close to the end-year. I supose that it is not a quincedence and originated from people looking for gifts and leaving impressions on such posts. *Suggestion: Post at these periods more often to attract even more customers.*
  2. Now we see that huge spikes in new customer traffic originated from viral posts on **facebook** and **instagram**.
