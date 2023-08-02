
# Credit Card Fraud Detection Model

This project was aimed at detecting if transactions made on a credit card are fraudulent or legal.


## 🔖 Features
| Column  | Description |
| ------------- | ------------- |
| Time | a unique Time per transaction  |
| v1 - v28 | a unique identifier transactaion time |
| Amount | Amount per transaction |
| class | ranges from 0 to 1 identifies fraud or legal transaction |

## Workspace Setup 👨‍💻
```python
import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
```
## Contributing ➕

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Authors ✍️

- [@Psalmykrane](https://www.github.com/Psalmykrane)
