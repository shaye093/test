```python
import numpy as np
import matplotlib.pyplot as plt
from matplotlib.lines import Line2D
x = np.random.rand(100)
y = np.random.rand(100)

markerindex = np.random.randint(0, len(Line2D.markers), 100)
for k, m in enumerate(Line2D.markers):
    i=(markerindex == k)
    plt.scatter(x[i], y[i], marker=m)
plt.show()
```

```python
print('hello',end='')
print('oooooowrold')
```

>`print` ('hello',end='')

