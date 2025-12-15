SELECT State, AVG(Total_Revenue) AS Average_Revenue
FROM `mtn_customer_churn`
group by State
order by Total_Revenue DESC
limit 10;


SELECT * 
FROM `mtn_customer_churn` 
WHERE State = 'Lagos'
and Gender = 'Male'

SELECT * 
FROM `mtn_customer_churn` 
WHERE Total_Revenue >= 500
and Customer_Churn_Status = 'Yes'
