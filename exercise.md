---
jupytext:
    text_representation:
        extension: .md
        format_name: myst
kernelspec:
    display_name: Python 3
    language: python
    name: python3
---


# Creating an Example


## Adding code cells


```{code-cell} python3

import ray
```


## Hiding and removing cells


```{code-cell} python3
:tags: [hide-cell]
# This can be useful if you don't want to clutter the page with details.

import ray
import ray.rllib.agents.ppo as ppo
from ray import serve
```
