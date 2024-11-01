# Square Root Formula
A new mathematical way of obtaining xˆ2, homoiconically, where x is the square root in the formula


For a given `x`, the identity is:

![image](https://github.com/user-attachments/assets/ab189ad8-2645-4557-bd42-18c22065aa79)

Where, x(x-1) is the summation of x as follows:

![image](https://github.com/user-attachments/assets/b0ee3ea1-547b-482f-b055-9913174b6c9d)
![image](https://github.com/user-attachments/assets/cbe12aa8-a8c9-47d0-a823-0bc1d4438aff)


#### CODE SNIPPET 
```python
def square(x):
    return ((x * (x + 1)) + (x * (x - 1))) / 2
```
