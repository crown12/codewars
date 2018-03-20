# Sum of Digits / Digital Root
[*View on Codewars*](https://www.codewars.com/kata/sum-of-digits-slash-digital-root)

In this kata, you must create a `digital root` function.

A digital root is the _recursive sum of all the digits in a number._ Given _n_, take the sum of the digits of _n_. If that value has two digits, continue reducing in this way until a single-digit number is produced. This is only applicable to the natural numbers.

Here's how it works (Ruby example given):
```ruby
digital_root(16)
=> 1 + 6
=> 7

digital_root(942)
=> 9 + 4 + 2
=> 15 ...
=> 1 + 5
=> 6

digital_root(132189)
=> 1 + 3 + 2 + 1 + 8 + 9
=> 24 ...
=> 2 + 4
=> 6

digital_root(493193)
=> 4 + 9 + 3 + 1 + 9 + 3
=> 29 ...
=> 2 + 9
=> 11 ...
=> 1 + 1
=> 2

```

__<font color="red">Note for Java users: actual and expected are flipped in the error messages.</font>__

## Timeline
- Created: 2014-09-19
- Published: 2014-09-19
- Approved: 2014-09-22
- Completed: 2015-05-05