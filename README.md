# Trading_bot

![An image for the header of the Repository](/Images/bot.png)

This application helps a team to create a model that predict wheather startups will be successful if funded by Alphabet Soup



## Technologies
This platform uses `python 3.7.13` with the following libraries imported in the first code block includes: `Pandas`, `scikit-learn`, `pathlib`, and `TensorFlow`.

---
## Installation Guide 

In case Pandas library is not available, run the following code in your terminal:

```python

pip install pandas
```


To install `scikit-learn`, `TensorFlow` make sure your Conda `dev` environment is active, run the following command:

```python
pip install -U scikit-learn
```

```python
pip install --upgrade tensorflow

```


To confirm the  installation, run the following code in your terminal:

```python
conda list scikit-learn
 ```
 
---

## Usage

Libraries that we had to import are the following:

```
import pandas as pd
import numpy as np
from pathlib import Path
import hvplot.pandas
import matplotlib.pyplot as plt
from sklearn import svm
from sklearn.preprocessing import StandardScaler
from pandas.tseries.offsets import DateOffset
from sklearn.metrics import classification_report

```

---
## Contributors

Baha Amour
---

## License

MIT.
