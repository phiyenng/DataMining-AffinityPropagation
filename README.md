# Market Basket Analysis using Equivalence Class Clustering and bottom-up Lattice Traversal Algorithm
------------------------  

## What is this project?  

## What is this project?  

In a highly competitive market, understanding consumer shopping habits is essential for e-commerce platforms, supermarkets, and online stores to attract and retain customers. Market Basket Analysis helps businesses optimize product placement, design promotions, and enhance the shopping experience. This project applies the ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal) algorithm to discover frequent itemsets and association rules from transaction data. Additionally, the performance of ECLAT is evaluated and compared with Apriori and FP-Growth algorithms.

------------------------  

## Data Source  
- **Data Origin**: The dataset was sourced from our professor (Market Basket Analysis 1)
- **Files**:  
   - `KPDL_Nhóm-12.ipynb`: Source code.
  
---

## Dependencies

Ensure the following libraries are installed before running the program:

### Data Processing Libraries:
```bash
pip install pandas numpy
import time
import math
import re
import itertools
import warnings
```

### ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal) Algorithm Libraries:
```bash
pip install pyECLAT

from pyECLAT import ECLAT
```

### Apriori & FP-Growth Algorithms Libraries:
```bash
pip install mlxtend

from mlxtend.preprocessing import TransactionEncoder
from mlxtend.frequent_patterns import association_rules
from mlxtend.frequent_patterns import apriori
from mlxtend.frequent_patterns import fpgrowth
```

### Visualization Libraries:
```bash
import seaborn as sns
import matplotlib.pyplot as plt
import plotly.express as px
```

------------------------  

### Our Contributors:    
- Nguyễn Vân Phi Yến
- Nguyễn Thành Vinh
- Trầm Thái Tú
- Huỳnh Ngọc Khánh Vy

### Course Information:
- Course: Data Mining
- Professor: PhD. Nguyễn An Tế
