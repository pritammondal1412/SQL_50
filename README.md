
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
```

[595 - Big Countries](https://leetcode.com/problems/big-countries/description/?envType=study-plan-v2&envId=top-sql-50)

```sql
select name,population,area 
from World where 
area>=3000000 
OR population>=25000000;
```

[1148 - Article Views I](https://leetcode.com/problems/article-views-i/description/?envType=study-plan-v2&envId=top-sql-50)

```sql
select distinct author_id as id
from Views 
where author_id = viewer_id
ORDER BY author_id;
```

[1683 - Invalid Tweets](https://leetcode.com/problems/invalid-tweets/description/?envType=study-plan-v2&envId=top-sql-50)

```sql
select tweet_id 
from Tweets
where LENGTH(content)>15;
```
