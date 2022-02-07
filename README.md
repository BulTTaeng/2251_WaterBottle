# 2251_WaterBottle

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/2251_WaterBottle/blob/main/2251_pro.PNG)

## What Algorithm should I use?

Graph Algorithm , BFS

## What was the key point and the hard part?

By using 3d visit array , save the water in bottle a , b ,c (visit[a][b][c])

There is 6 cases that we can do.

a->c , a->b , b->a , b->c , c->a , c->b

There is 2 case when filling the water bottle.

1. left space in receiving bottle is bigger than giving bottle.

2. left space in receiving bottle is smaller than giving bottle.

Keep checking does case and range and do bfs. If a bottle have no water , ans[water in c] will be true.(which means that is possible).

After these sequence, ans array will have the answer.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
