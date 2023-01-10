# Function Summary

## Pandas

* If column is category type, i drop index but category remain.

```python
# CONFIG column is category type
df = df.drop(df[df["CONFIG"] == "A"].index)
df = df.cat.remove_unused_categories()          # to remove unuse category
```

* Random sample

```python
df = df.sample(n = 1000, random_state = 1) 
```


## Numpy


## matplotlib

* show graph in jupyter notebook

%matplotlib inline

* stop making broken "-" in plt 
```python
plt.rcParams['axes.unicode_minus'] = False
```
