# Lemonade-Change
Leetcode Problem #860. Calculate if change is possible for given amount.

# Lemonade Change

At a lemonade stand, each lemonade costs **$5**. Customers are standing in a queue to buy from you and order one at a time (in the order specified by the `bills` array). Each customer will only buy one lemonade and pay with either a **$5**, **$10**, or **$20** bill. 

You must provide the correct change to each customer so that the net transaction is that the customer pays $5.  
**Note:** You do **not** have any change in hand at first.

## Problem

Given an integer array `bills` where `bills[i]` is the bill the *i-th* customer pays, return `true` if you can provide every customer with the correct change, or `false` otherwise.

## Examples

### Example 1

```text
Input: bills = [5, 5, 5, 10, 20]  
Output: true  

Explanation:  
From the first 3 customers, we collect three $5 bills in order.  
From the fourth customer, we collect a $10 bill and give back a $5.  
From the fifth customer, we give a $10 bill and a $5 bill.  
Since all customers got correct change, we return true.
```

### Example 2

```text
Input: bills = [5, 5, 10, 10, 20]  
Output: false

Explanation:  
From the first two customers in order, we collect two $5 bills.  
For the next two customers, we collect a $10 bill and give back a $5 bill.  
For the last customer, we cannot give the change of $15 back because we only have two $10 bills and no $5 bill.  
Since not every customer received the correct change, we return false.
```
---
