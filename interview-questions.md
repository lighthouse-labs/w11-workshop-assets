# Interview Questions

1. Assuming the following basic  table structure

    ```sql
    Documents (DocID, DocDate)
    Keywords (KeyWordID, KeyWord)
    DocumentKeywords (DocID,KeywordID)
    ```

    Write a query to return the following:
    ```
    Part 1: Documents with a DocDate after 4/1/1995  
    Part 2: Documents that contain the keyword "Blue"  
    Part 3: Documents that contain the either the keyword "Blue" or "Yellow"
    Part 4: Documents that contain the both the keywords "Blue" and "Yellow"
    ```

2. Given an array of distinct integer values, count the nuber of pairs of integers that have difference k. For example given the array `[1, 7, 5, 9, 2, 12, 3]` and the difference `k = 2`, there are four pairs with difference 2: `(1,3), (3, 5), (5, 7), (7, 9)`

3. Implement a function to determine if a string has all unique characters.

4. Write a function to replace all the spaces in a string with `%`.

5. Given a string, write a function to check if it is a palindrome. A palindrome is a word or phrase that is the same forwards and backwards. 

6. Draw an ERD for a database with companies, people and professionals (people who work for companies)

7. Write a function to print all numbers between 1 and 100.
    7a. How would you modify the function to print all numbers between 1 and 1000, 10000, or n ?

8. How do you find the largest and smallest number in an unsorted integer array?

9. How can a given string be reversed using recursion?

10. Given an array called `stockPrices`, where:

    - The indices are the time (in minutes) past trade opening time, which was 9:30am local time.
    - The values are the price (in CAD dollars) of one share of Apple stock at that time.

    Write an efficient method that takes `stockPrices` and returns the best profit one could have made from one purchase and one sale of one share of Apple stock yesterday.

11. Write a function that, given:

     - an amount of money
     - an array of coin denominations
     - computes the number of ways to make the amount of money with coins of the available denominations.

    Example: for `const amount = 4` (4¢) and `const denominations=[1,2,3]`(1¢, 2¢ and 3¢), your program would output 44 — the number of ways to make 4¢ with those denominations:

    ```
    1¢, 1¢, 1¢, 1¢
    1¢, 1¢, 2¢
    1¢, 3¢
    2¢, 2¢
    ```



