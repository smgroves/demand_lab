# demand_lab

A simulated, price-sensitive market for the Understanding Uncertainty inference lab.

Run in Google Colab (the module is compiled for Linux, Python 3.13):

```python
!git clone -q https://github.com/smgroves/demand_lab.git
%cd /content/demand_lab
from demand import demand

responses = demand(price=14.0)   # one market test: 1 = bought, 0 = didn't
print(len(responses), responses.sum())
```

Each market test takes a while to run.
