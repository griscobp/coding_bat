# monkey_trouble

We have two monkeys, a and b, and the parameters a_smile and b_smile indicate if each is smiling. We are in trouble if they are both smiling or if neither of them is smiling. Return True if we are in trouble.

```python
monkey_trouble(True, True) --> True
monkey_trouble(False, False) --> True
monkey_trouble(True, False) --> False
```

## Project Log

In this project, it was much faster than the first one becuase I was able to use what I learned from the previous one here. I was able to get my code even shorter, becuase I realized that i could just return the result of the Boolean exppression, rather than returning an explicit `True` or `False`.