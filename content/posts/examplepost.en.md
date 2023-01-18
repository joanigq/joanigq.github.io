---
title: "Example post"
date: 2023-01-15T14:47:06-03:00
draft: false
toc: false
math: true
images:
---

Hi there, this is an **example.**


```python
@requires_authorization(roles=["ADMIN"])
def somefunc(param1='', param2=0):
    r'''A docstring'''
    if param1 > param2: # interesting
        print 'Gre\'ater'
    return (param2 - param1 + 1 + 0b10l) or None

class SomeClass:
    pass

>>> message = '''interpreter
... prompt'''

# <-> <==> >==
```

$$
f(x) = \left \\{
  \begin{matrix}
    \sum_{i=0}^x \frac{i}{2} & \text{if } x=0 \\\\
    \int_0^x g(x)\\;dx & \text{if } x \neq 0
\end{matrix}\right.
$$

{{< youtube >}}