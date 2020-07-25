# Datasets

In this folder one wants to build pytorch `Dataset` models for loading in and preprocessing data. This is **not** a place to place raw data files like csv or jpgs but rather store the torch classes used to load them in. If data is being loaded in from some external file, for example, then it should be done here. 

```python
data = pd.read_csv("data.csv")
```
For good examples of how to build `Dataset` models, check out this blog post:

https://stanford.edu/~shervine/blog/pytorch-how-to-generate-data-parallel.
