# Potato Chips Retail Strategy and Analytics

The project is a compilation of analytics done for potato chips retail. 
<i>The Potato Chips division of a Retail Store wants to analyze Sales performance based on various customer demographics. Based on the analysis, the division wants to strategize business plans that will be implemented for the next 6 months. </i>

The datasets used for this project are: 

- **QVI_transaction_data.xlsx**: transaction data for all the products sold at the retail store between 01-July-2018 and 30-June2019

|Column Name | Column Description |
| --- | --- |
| Lylty_card_nbr | loyalty card ID of the customer |
| Lifestage | lifestage of the customer - young, old / family, single etc. |
| Premium | loyalty group of the customer, based on Retail Store's loyalty classification |

- **QVI_purchase_behaviour.csv**: dataset contains information about all the customers of the retail store  

|Column Name | Column Description |
| --- | --- |
| Date | date of transaction |
| Store_nbr | Retail chain's store number where transaction was done |
| Lylty_card_nbr | loyalty card ID of the customer |
| Txn_ID | Transaction identifier |
| Prod_nbr | Product code |
| Prod_name | Prodcut description |
| Prod_Qty | Product quantity purchased in units |
| Tot_sale | Total sales for all units of a product purchased |

The project was divided into two parts: 

<b>Part1 - Customer Purchase Behavior Analytics: </b>
The customers data set and the transaction data set was combined together to analyze and identify common patterns for potato chips sale. Based on the product preference findings, it was suggested to increase product visibility to customer segments by placing the products in their preferred section of the retail. That is the retail section where the consumer segments frequent the most. 

<b>Part 2 - Store Trial Layout Analysis: </b>
Based on the recommendations of customer purchase behavior analysis, 3 stores were chosen for layout re-design. The layouts were trialed for 3 months. The analysis was to identify if the trial layouts were successfull in increasing customers footfalls at the store and sales for potato chip products. 

<b>Additional notes:</b>
I took up this project to be a good opportunity to work and learn Plotly graphing libraries. Alas, the plots are not rendered by github. Hence, please access the below given URL's to open the project in nbviewer. 

https://nbviewer.jupyter.org/github/simplyrucha/InsideSherpa_QuantiumVI/blob/master/Chips_Part1.ipynb

https://nbviewer.jupyter.org/github/simplyrucha/InsideSherpa_QuantiumVI/blob/master/Chips_Part2.ipynb

(Click ctrl+left to open in new tab)
