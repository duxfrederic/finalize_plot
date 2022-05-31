# finalize-plots

## Installation
```bash
pip install finalize-plots
```

## Usage:
```python
import matplotlib.pyplot as plt
from finalize_plots import finalize 

fig = plt.figure()
plt.plot([1,2,3],[2,3,5])
finalize(fig)
plt.show()
```
