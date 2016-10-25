# lapandasds
##5. Plotting
###1 Inline plotting
```
import pandas as pd
import numpy as np
inport matplotlib pyplot as plt
plt.style.use('ggplot')
mu,sigma = 100,15
data_set = mu + sigma + np.random.randn(1000)
n,bins,patches=plt.hist(data_set,50,normed=1,facecolor='o',alpha=0.75)
plt.xlabel('smarts')
plt.ylabel('probability')
plt.title('Histogram')
plt.text(40,.025,r'$\mu=100,\ \sigma=15$')
plt(axis[40,160,0,0.03])
plt.grid(True)
plt.show()
```
