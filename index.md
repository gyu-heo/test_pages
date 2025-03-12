---
title: Home
layout: default
nav_order: 1
permalink: /
math: true
---

# Welcome to the Documentation

This is the home page for the documentation site.

## Features of this site

* **LaTeX Support** - Write beautiful mathematics with MathJax
* **Organized Navigation** - Directory-based organization like a textbook
* **Theme Toggle** - Choose between light, warm (default), and dark themes
* **Previous/Next Navigation** - Easy movement between pages

## Examples

### LaTeX Example

Here's an inline equation: $E = mc^2$

And a display equation:

$$
\begin{align}
\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} & = \frac{4\pi}{c}\vec{\mathbf{j}} \\
\nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\
\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\
\nabla \cdot \vec{\mathbf{B}} & = 0
\end{align}
$$

### Code Example

```python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        a, b = b, a + b
    return a

# Print the first 10 Fibonacci numbers
for i in range(10):
    print(fibonacci(i))
```

## Quick Links

* [Directory 1](dir1/) - First section of documentation
* [Directory 2](dir2/) - Second section of documentation
