Installation:
```bash
pip install finalize_plot
```

Simple test: (run the installation part first to have the correct libraries installed)
```bash
unzip finalize_plots.zip
cd finalize_plots/tests/
python test.py
```

Usage:
```python
import matplotlib.pyplot as plt
from finalize_plots import finalize 

fig = plt.figure()
plt.plot([1,2,3],[2,3,5])
finalize(fig)
```
