# Corporaci-n-Favorita-Grocery-Sales-Forecasting
This Case Study is all about forecasting unit sales of items for the Ecuadorian supermarket chain 'Corporación Favorita' to improve inventory management.
Corporación Favorita is a large Ecuadorian-based grocery retailer which operate hundreds of supermarkets, with over 200,000 different products on their shelves.

Objective -> Predicting the unit sales for 16 days in future for thousands of items sold at different Favorita stores located in Ecuador.

Business Problem -> The Grocery Retailer (Corporación Favorita) can basically face two of the following problems:

		   1. Stock-out- A situation in which an item is out of stock.
		                The problem of Stock-out (i.e popular items quickly sell out, leaving money on the table and customers fuming ) 
		                causes an increased risk of lost sales, since customers are more likely to look elsewhere for the necessary items,
                                which in-turn can be a huge opportunity loss for the retailer.

		   2. Overstock- A situation in which an item is present in more quantity than is necessary or required.
				 The problem of Overstock can potentially cost drastic amounts of money as products just sit on shelves where they are not 
                                 being utilized. Depending on their type, they can get spoiled which would cause a total loss for the retailer.
			
		   So the above mentioned problems can be solved by accurately predicting the unit sales for individual items.
		   
		  Being able to predict the amount sold will enable them to better organize their logistical operations. 
                  This will potentially cut both opportunity-costs introduced by stock-outs and storage costs introduced by over-stocking.

Hence an accurate forecasting model can greatly increase supermarket revenue and is generally of great importance to the organization as it improves profit as well as 
provides insights into the way customers can be better served.

Dataset used -> https://www.kaggle.com/c/favorita-grocery-sales-forecasting/data

* Training Data includes the target unit_sales by date, store_nbr, and item_nbr and a unique id to label rows.
* Test data includes date, store_nbr, item_nbr combinations that are to be predicted, along with the onpromotion information.
* Store metadata includes city, state, type, and cluster (cluster is a grouping of similar stores)
* Item metadata includes family, class, and perishable.
* Transactions Data includes the count of sales transactions for each date, store_nbr combination. Only included for the training data timeframe.
* Oil Data includes daily oil price. Includes values during both the train and test data timeframe.
* Events Data includes Holidays and Events, with metadata
