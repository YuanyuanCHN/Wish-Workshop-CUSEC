# Wish-Workshop-CUSEC
Wish-Workshop-Intro to Data Science &amp; PM with SQL - A Real World Case Study of Wish

Please open online SQL IDE https://www.jdoodle.com/execute-sql-online/ 

Run the Create_Tables.sql content before runing your own code.

Table schema as below:

**Sales**:
* transaction_id int
* date date
* user_id int 
* merchant_id int
* product_id char
* quantity int 
* price double
* destination_cntry char

**Refunds**:

* transaction_id int
* purchase_date date
* refund_date date
* product_id char
* refund_quantity int
* refund_reason char
* refund_status int
