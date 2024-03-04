# Comprehensive-market-data-analysis
#### An comprehensive data analysis of a particular market and its customers.

<h2 style="line-height:200%;font-family:vazir;color:#0099cc">
<font face="vazir" color="#0099cc">
The Dataset
</font>
</h2>



<p  style="text-align: justify;line-height:200%;font-family:vazir;font-size:medium">
<font face="vazir" size=3>
The data of this project is available in the Excel file <code>sales.xlsx</code> and the descriptions of the columns of the dataset are given in the table below.
</font>
</p>

<center>
<div  style="line-height:200%;font-family:vazir;font-size:medium">
<font face="vazir" size=3>
    
|Column|Description|
|:------:|:---:|
|<code>InvoiceNumber</code>|A 6-digit number uniquely assigned to each invoice. If the beginning of this number starts with the letter C, it means that the invoice has been canceled.|
|<code>ProductCode</code>|A 5-digit number that is uniquely assigned to each type of product.|
|<code>ProductName</code>|Product's name|
|<code>Quantity</code>|The number of orders of a product type in the invoice|
|<code>InvoiceDate</code>|Invoice creation date|
|<code>UnitPrice</code>|The price of a product type per unit|
|<code>CusotmerId</code>|A 5-digit number that is uniquely assigned to each customer.|
|<code>Country</code>|The name of the customer's country of residence|

</font>
</div>
</center>

This project has 5 steps:

<ol>
  <li><code><b>Data preprocessing</b></code>: A series of preprocessing steps are performed on the entire data, such as handling the missing data</li>
  <li><code><b>Exploration</b></code>: I answer a series of high-level questions and obtain an intuitive view of the company's financial information.</li>
  <li><code><b>Study of target markets</b></code>: I will analyze different locations of sale and supply and I will check which countries, despite having many customers, experience little sales.</li>
  <li><code><b>Customer value</b></code>: Using the RFM practical criteria, I divide the company's customers into 7 categories, each of which has its meaning and behavior in terms of marketing.</li>
  <li><code><b>Customer retention rate analysis</b></code>: What percentage of customers buy from this company in the following months after their first purchase.?</li>
</ol>

<br><em><b>I only used Numpy, Pandas, Matplotlib, and Seaborn in this project</b></em>
