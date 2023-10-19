# Financial-Analysis-Company-X

## Financial Analysis

Company X manufactures a couple of products one of the products is Paseo. The analysis of the product "Paseo" and its revenue performance based on the recent financial dataset shows that the average revenue for "Paseo" is $163,421.50. However, the overall average revenue for all products in the dataset is slightly higher, at $169,609.07. It's worth noting that the total revenue for all products in the dataset is a significant $118,726,350.26.

These findings suggest that "Paseo" generates a lower average revenue compared to our entire product portfolio, contributing to the slightly lower overall average revenue. In the context of our company's revenue, "Paseo" represents a relatively smaller portion of the total.

To increase revenue, it is beneficial to explore strategies to enhance the performance of "Paseo.".
## Formula Used =AVERAGEIF(K2:K701,"Paseo",A2:A701)

![](https://github.com/TomiiOkotie/Financial-Analysis-Company-X/blob/main/revenue.png)

The dataset comprises a total of 700 sales, with a substantial portion, 400 sales, attributed to the mid-market and government segments. This allocation underscores the significance of these segments within the sales landscape. It’s clear that the mid-market and government segments play a pivotal role in the company's sales. Focusing on these segments and tailoring strategies to their specific needs can ensure continued success and potential growth in these key areas.  Considering the prominence of the mid-market and government segments in sales, it's wise to assess their growth potential and formulate strategies to maximize their impact on the revenue. This might involve tailoring the products or services to better suit the needs of these segments.
## Formula Used =COUNTIFS(N2:N701,"Government")+COUNTIFS(N2:N701,"Midmarket")

![](https://github.com/TomiiOkotie/Financial-Analysis-Company-X/blob/main/NumberofSales.png)


This insight highlights that "Montana" is a substantial revenue generator for our company in the Canadian market. It's crucial to recognize the success of this product in Canada and potentially consider strategies to maintain and further expand its presence in this market to maximize revenue. Understanding what contributes to "Montana's" success in Canada can provide valuable insights for other products and markets as well.
## Formula Used =SUMIFS(A2:A701,C2:C701,"Canada",K2:K701,"Montana")

![](https://github.com/TomiiOkotie/Financial-Analysis-Company-X/blob/main/MontanaCanada.png)

In December, the total profit was $2,717,329.98 out of a total profit of $16,893,702.26. This means that December's profit accounted for approximately 16.11% of the total annual profit. 
## Formula Used =SUMIF(I2:I701,"December",L2:L701)

![](https://github.com/TomiiOkotie/Financial-Analysis-Company-X/blob/main/TotalDecember.png)


In the analysis of sales data, several noteworthy insights have emerged, shedding light on crucial trends and performance indicators within our organization. One of the standout findings is the dominance of the ## United States as the top-selling country in the dataset. The  ## Government sector emerges as the segment with the highest unit of goods sold. ## April has proven to be the peak month for unit goods sold according to our data.
## Formula Used =INDEX(C2:C701,MATCH(MAX(O2:O701),O2:O701,0))  Country
## Formula Used =INDEX(N2:N701,MATCH(MAX(O2:O701),O2:O701,0))   Segment
## Formula Used =INDEX(I2:I701,MATCH(MAX(O2:O701),O2:O701,0))   Month



![](https://github.com/TomiiOkotie/Financial-Analysis-Company-X/blob/main/AdvanceCount.png)


![](https://github.com/TomiiOkotie/Financial-Analysis-Company-X/blob/main/AdvanceFunction.png)





