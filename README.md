The task is to create new international bank account based on a given imput. Imput can be found in the link below. 

First of all, had to remove dashes from a bank sort code within the transactionas table to derive 6 characters of numbers. 

I added a new coulumn called country_code to the existing translations table. I filled each row with value called GB. 

To get the international account number, the task required to join two tables, that is, transactions and swift_codes.

I then created a cte out of the new table I joined. 

I used the concat function to join the columns of the cte to derive the international account number for each transation_id in accordance of the format provided by the task. 

Below is the link to the task

https://preppindata.blogspot.com/2023/01/2023-week-2-international-bank-account.html?m=1
