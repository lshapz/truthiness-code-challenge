# Truthiness Code Challenge

## Objectives

1. Strengthen your understanding of truthiness in Ruby
2. Practice using boolean and comparison operators

???

### Code Challenge I

Take a look at the code below. We have defined a method, `returning_true` that uses a comparison operator, the `<` (less than) to compare the number 14 to... nothing.

?: What value(s) for `?` will make `returning_true` return `true`?

``` ruby
def returning_true
  14 < ?
end
```

( ) 1
(x) 15
( ) 14
(x) 17


Here we have a method, `returning_false` that uses both comparison and boolean operators.

?: What value(s) for `?` will make `returning_false` return `false`?

``` ruby
def returning_false
  7 > 4 && 100 < ?
end
```

(x) 100
( ) 101
( ) 102
( ) 103

### Code Challenge III

Take a look at the method `using_truthiness` below.

?: What value(s) for `?` will make `using_truthiness` return `false`?


```ruby
def using_truthiness
  7 > 8 || ?
end
```

(x) false
(x) 8 > 9
(x) !true
(x) 9 < 6


?: What value(s) for `?` will make `using_truthiness` return `true`?


```ruby
def using_truthiness
  7 > 8 || ?
end
```

(x) 7 > 6
( ) 7
( ) false
( ) 8 > 9

???

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/truthiness-code-challenge' title='Truthiness Code Challenge'>Truthiness Code Challenge</a> on Learn.co and start learning to code for free.</p>
