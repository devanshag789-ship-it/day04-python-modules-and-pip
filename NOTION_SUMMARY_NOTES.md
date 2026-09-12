# #Day 4: Python Modules & pip

## What are Modules?

Modules are Python files containing functions, classes, and variables created by others and that you can reuse in your programs. They help organize code and avoid repetition.

### Types of Modules

**Built-in Modules** - Come pre-installed with Python (e.g., `math`, `random`, `datetime`)

**Third-party/External Modules** - Created by the community and installed via pip (e.g., `numpy`, `pandas`, `requests`)

### Using Modules

```python
# Importing module
import math
print(math.sqrt(16))

# Import specific function
from math import sqrt
print(sqrt(16))

# Import with alias
import pandas as pd
```

---

## What is pip?

**pip** is Python's package installer. It allows you to install, upgrade, and manage third-party packages from the Python Package Index (PyPI).

### Essential pip Commands

**Install a package**

```python
pip install package_name
```

**Install multiple packages**

```python
pip install package1 package2 package3
```

**Upgrade a package**

```python
pip install --upgrade package_name
```

**Uninstall a package**

```python
pip uninstall package_name
```

**List all the installed packages**

```python
pip list
```

**Show package details**

```python
pip show package_name
```

**Create requirements file**

```python
pip freeze > requirements.txt
```

**Install from requirements file**

```python
pip install -r requirements.txt
```

### Common Use Cases

> **Installing Popular Libraries**
> 

```python
pip install numpy pandas matplotlib requests
```
