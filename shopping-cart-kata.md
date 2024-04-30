## Simply Business Shopping Cart Kata

**Constraints**
- A few minutes to ask clarifying questions
- 45 minutes to complete as much as possible
- Google, StackOverflow, etc are allowed
- No pre-prepared answers or ChatGPT solutions will be accepted
- Treat this as pair programming, we want to hear how you think and see what you search

-----

### Problem Description

Some things in supermarkets have simple prices, but discounts can produce more complex prices. Write a program that, given a list of items purchased, will print out an itemized receipt and total cost. You can print out to the command line or display on a simple webpage, whatever you prefer.

**Example Output**
```
    1 can of beans
    3 cans of soda
    1 paper towel roll
    ----
    Total: $7.70
```

Here's a stock list with pricing and discount rules:

**Stock Pricing**

- Beans: $1.20 per can
- Soda: $1.50 per can
- Bagels: 75¢ each
- Paper Towels: $2.50 each

**Discount Rules**

- Beans: Buy 2 get 1 free
- Soda: $4 for 3 cans
- Bagels: $7 per dozen or $4 per 1/2 dozen
- Paper Towels: No discount

*Note: Discounts are applied to the exact number of items, any more or less receive regular pricing.*  
**Example**: 4 cans of beans would cost $3.60 (3 cans for $2.40, 1 can for $1.20)

-----

### Shopping Cart Use Cases to Test Against

#### Input 1: 
```
    1 can of beans
    1 soda
```

#### Input 2: 
```
    1 soda
    12 bagels
```

#### Input 3
```
    6 cans of beans
    3 sodas
```

#### Input 4
```
    10 cans of beans
    4 sodas
    15 bagels
    2 rolls of paper towels
```
