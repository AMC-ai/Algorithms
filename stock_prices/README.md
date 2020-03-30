# Stock Prices

You want to write a bot that will automate the task of day-trading for you while you're going through Lambda. You decide to have your bot just focus on buying and selling Amazon stock. 

Write a function `find_max_profit` that receives as input a list of stock prices. Your function should return the maximum profit that can be made from a single buy and sell. You must buy first before selling; no shorting is allowed here.

For example, `find_max_profit([1050, 270, 1540, 3800, 2])` should return 3530, which is the maximum profit that can be made from a single buy and then sell of these stock prices. 

## Testing

Run the test file by executing `python test_stock_prices.py`.

You can also test your implementation manually by executing `python stock_prices.py [integers_separated_by_a_single_space]`

## Hints

 For this problem, we essentially want to find the maximum difference between the smallest and largest prices in the list of prices, but we also have to make sure that the max profit is computed by subtracting some price by another price that comes _before_ it; it can't come after it in the list of prices. 

 So what if we kept track of the `current_min_price_so_far` and the `max_profit_so_far`? 

 process for Algos

-Identify the input 
amazon stalk prices

-Identify the output 
return the maximum profit that can be made from a single buy and sell

-Identify all the initial variables you may need you can always change these later
    stock prices


-Are you going to need a loop? If you know the length use a for loop if you don't know the length use a while loop. 

Although this isn't a set-in-stone rule its a good one to follow.
-How is your information stored? Are you using a list,dict,string…?
-Then just start coding… researching different methods in order to accomplish a task you want is encouraged and is how you learn to get better at Algos!