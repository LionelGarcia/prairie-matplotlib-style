# prairie-matplotlib-style
Personal matplotlib style



**Usage**:

```python
from matplotlib import pyplot as plt
import prairie_matplotlib_style as pr

pr.use()

fig = plt.fig()
axe = fig.add_subplot(111)

# ...

pr.style(axe)
```