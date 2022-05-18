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



# for liverpool fc
first,as a liverpool fan,i am happy to know that we win Southampton fc.But the Manchester City fc will face Aston Villa fc.It will tells us who is the champion in 2021-2022.
We successfully enter final of the Eurpean Cup,we will face real mardrid fc.It will be a nice race.I hope we can be the winner.
                                                                                                                      -- 2022-05-18 20:43
