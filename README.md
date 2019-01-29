# prairie-matplotlib-style
Personal matplotlib style

![cold plot](https://github.com/LionelGarcia/prairie-matplotlib-style/blob/master/doc/cold%20colors_plot.png)
![hot plot](https://github.com/LionelGarcia/prairie-matplotlib-style/blob/master/doc/hot%20colors_plot.png)

**Usage**:

```python
from matplotlib import pyplot as plt
import prairie_matplotlib_style as pr

pr.use()
pr.use_colors('cold')

fig = plt.figure()
axe = fig.add_subplot(111)

# ...

pr.style(axe)
```