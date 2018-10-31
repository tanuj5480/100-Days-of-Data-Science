**Linear regression assumptions and their validation**

## Importing the libraries

```python
import numpy as np
from sklearn.linear_model import LinearRegression
```

## Creating both linear and non-linear data
```python
np.random.seed(20)
x = np.arange(20)

x_reshape = x.reshape(-1,1)

y_linear = [x*2 + np.random.rand(1)*4 for x in range(20)]
y_nonlinear = [x**3 + np.random.rand(1)*10 for x in range(20)]
```

## Fitting the model with sklearn

```python
linear = LinearRegression()
linear.fit(x_reshape, y_linear)
```
