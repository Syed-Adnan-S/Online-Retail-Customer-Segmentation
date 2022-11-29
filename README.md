# Online Retail Customer Segmentation

### <b>Description:</b>
This is an unsupervised machine learning capstone project on customer segmentation, given by [Alma Better](https://www.almabetter.com/).

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Problem statement:</b>
In this project, Our main task is to identify major customer segments on a transactional data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail company.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. 

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Data description (Columns involved):</b>

* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Business context of the problem:</b>

#### <b>Customer Segmentation:</b>
Customer segmentation is the process by which you divide your customers up based on common characteristics so you can market to those customers more effectively.

![pic2](https://user-images.githubusercontent.com/85065799/204151765-54a15ea0-b073-4746-abd9-4b95fa685312.jpg)

#### <b>Different ways of segmentation:</b>

1. Demographic segmentation.
2. Behavioral segmentation.
3. Geographic segmentaion.
4. Needs based segmentation.
  
  and many more... 
  
#### <b>Benefits of customer segmentation:</b>
1. Organised customer bases.
2. Targeted communication becomes easy.
3. Choosing top sales prospects becomes easy.
  
  and many more...

![pic3](https://user-images.githubusercontent.com/85065799/204151805-1648d8ea-d291-4170-bafd-05615df181ee.jpg)

<b>In this project I'll be performing Behavioral segmentation using the classical RFM model.</b>

![pic4](https://user-images.githubusercontent.com/85065799/204151812-045c09d1-300b-4d6b-9c0a-1b62b3d2df69.png)

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Project Flowchart:</b>
1. Initial preparations(Loading the dependencies and the data).

2. Data Cleaning:
   * Data Exploration.
   * Handling null values.
   * Handling duplicate values.
   * Removing Outliers.
   * Removing Cancelled orders.

3. Feature Engineering:
   * Extracting columns from the InvoiceDate column.
   * Forming the total Amount column.
  
4. EDA.

5. Forming the segmentation criteria.

6. Pre Processing the data.

7. Model implementation:
   * K Means.
   * K Means with elbow method.
   * Hierarchical clustering (Agglomerative).

![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

### <b>Conclusion:</b>

#### <b>EDA insights:</b>
  * The product 'White hanging heart t-light holder' is the most frequently ordered product, around 1700 times. 'Jumbo bag red retrospot' is the second most ordered product, around 1300 times.
  * The product 'Pack of 72 retrospot cake cases' has the most quantity ordered, around 15,000 units. 'Assorted colour bird ornament' is second with around 13,000 units ordered.
  * The product "Product Bunting" has made the most money, around 35,000 sterling. "White Hanging heart T-light holder" being the second, which has made around 32,000 sterling.
  * The customer with the ID: 17841 has the highest number of orders and the customer with the ID: 18118 has the lowest number of orders.
  * United Kingdom has the most orders placed, with around 3 lakh orders. Germany being second, but way less than United Kingdom.
  * Most orders are made in the 12th hour, i.e 12pm to 1pm, and the least orders are made in the 6th hour, i.e 6am to 7am.
  * The 6th day of the month has the highest number of orders and the 31st day has the lowest.
  * Most of the orders are made on Thurday,around 66 thousand, and the least number of orders are made on Friday, around 46 thousand.
  * The most number of orders are made in the 11th month, i.e December, and the least in the 2nd month, i.e February.
  
#### <b>Model implementation conclusions:</b>
  * Simple K Means model has a silhouette score of 0.4361, a Calinski harabasz index of 2378 and a Davies Bouldin score of 1.03.
  * K Means model with elbow method has a silhouette score of 0.5233, a Calinski harabasz index of 4171 and a Davies Bouldin score of 0.688.
  * Agglomerative clustering has a silhouette score of 0.4958, a Calinski harabasz index of 3616 and a Davies Bouldin score of 0.711.
  * K Means model with elbow method is the best performing model.
  * Simple K Means model is the worst performing model.
  * Actions to take for each cluster:
      1. Perform targeted analysis and targeted advertisement for each cluster.
      2. Advertise products that can be presented with a discount to the customers in the lesser important clusters, which could convert the customers in these less important groups to customers of more important clusters.
  
#### <b>Challenges faced:</b>
  * Removing outliers.
  * Choosing the right approach for segmentation.
  * Choosing the right ML models and evaluation metrics.
  
![rainbow](https://user-images.githubusercontent.com/85065799/204543278-26c507b6-400a-42e0-852f-2e09362f6e12.png)

<b> For further information you can check the google colab file added in the repository. 

If you find any mistakes or have any suggestions for me, please reach out to me, all the criticism is heartly welcomed.

You can also reach out to me for project collaborations.

My Email Id - <u>syedshabbir107@gmail.com</u>

My LinkedIn profile - [Profile](https://www.linkedin.com/in/syed-adnan-s-2b899b228/)</b>

### Thankyou for tagging along to the end.
