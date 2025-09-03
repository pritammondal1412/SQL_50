
<<<<< SQL 50 - LeetCode >>>>>>

Solutions for [SQL 50](https://leetcode.com/studyplan/top-sql-50/) Sn on LeetCode

--------------------------------------------------------------------------------------

******************************************************************************************

[1757 - Recyclable and Low Fat Products](https://leetcode.com/problems/recyclable-and-low-fat-products/description/?envType=study-plan-v2&envId=top-sql-50)

```sql
select product_id 
from Products 
where low_fats="Y" and recyclable="y";
```

[584 - Find Customer Referee](https://leetcode.com/problems/find-customer-referee/?envType=study-plan-v2&envId=top-sql-50)

```sql
select name
from Customer
where referee_id!=2 OR referee_id IS NULL;

