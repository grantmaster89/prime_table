# prime_table

# Running
```
user/prime_table $ gem install bundler  
user/prime_table $ bundle install
user/prime_table $ ruby lib/prime_table.rb
```
# Sample Output
```
Welcome to the Prime table Generator
-------------------------
This program will print a multiplication table of prime numbers given a amount
4 attempts total
Type number of prime numbers you want otherwise default is 10:
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
|             Generate 10 prime numbers in a table             |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
|    | 2  | 3  | 5   | 7   | 11  | 13  | 17  | 19  | 23  | 29  |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 2  | 4  | 6  | 10  | 14  | 22  | 26  | 34  | 38  | 46  | 58  |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 3  | 6  | 9  | 15  | 21  | 33  | 39  | 51  | 57  | 69  | 87  |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 5  | 10 | 15 | 25  | 35  | 55  | 65  | 85  | 95  | 115 | 145 |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 7  | 14 | 21 | 35  | 49  | 77  | 91  | 119 | 133 | 161 | 203 |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 11 | 22 | 33 | 55  | 77  | 121 | 143 | 187 | 209 | 253 | 319 |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 13 | 26 | 39 | 65  | 91  | 143 | 169 | 221 | 247 | 299 | 377 |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 17 | 34 | 51 | 85  | 119 | 187 | 221 | 289 | 323 | 391 | 493 |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 19 | 38 | 57 | 95  | 133 | 209 | 247 | 323 | 361 | 437 | 551 |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 23 | 46 | 69 | 115 | 161 | 253 | 299 | 391 | 437 | 529 | 667 |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
| 29 | 58 | 87 | 145 | 203 | 319 | 377 | 493 | 551 | 667 | 841 |
+----+----+----+-----+-----+-----+-----+-----+-----+-----+-----+
Press n to quit or any other key to continue:
```

# Objective
Write a program that prints out a multiplication table of the first 10 prime numbers. The program must run from the command line and  print one table to STDOUT.
The first row and column of the table should have 10 primes, with each cell containing the product of the primes for the corresponding row and column.

# Notes
* Consider complexity. How fast does you code run? How does it scale?
* Consider cases where we want more than N primes.
* Do not use the Prime class from stdlib.
* Write tests. Demonstrate TDD/BDD

# Testing

```
user/prime_table $ rspec
```  
Press enter until all tests run