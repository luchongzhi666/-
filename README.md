# -
第一次使用
深度学习了mysql中的嵌套查询
第一次完整的不借助帮助完成嵌套类题目
select cust_email
from Customers
where cust_id in (
                  select cust_id
                  from Orders
                  where order_num in (
                                      select order_num
                                      from OrderItems
                                      where prod_id = 'BR01')
                  );


# about football
today i want to talk about sth about our chinese football.As a fan for this sport,nothing can make me speechless is that.
