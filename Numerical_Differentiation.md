![수치미분_200906_215044_1](https://user-images.githubusercontent.com/48379869/92326381-a4408180-f08c-11ea-8318-e9d59686a8cf.jpg)

# 구현
```python
def numerical_derivative(f, x):

    delta_x = 1e-4 #lim에 해당하는 작은 값

    return (f(x+delta_x))-(f(x-delta_x)) / (2*delta_x)
```
