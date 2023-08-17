---
title: Second Post
author: David Hintelmann
date: 2023-08-16
description: "This is a demo for testing out how the blog page will look when there are multiple posts."
tags: ["Markdown", "LaTeX","KaTeX"]
---
{{< katex >}}

# More Markdown for Math Formulas

Common formulas for perimeter, circumference, area, and volume.

First we will show Inline Notation and Block Notation. Don't forget to include `katex` into the article as KaTeX can be used to render mathematical notation. This shortcode is necessary for LaTeX/KaTeX to be rendered correctly.

### Inline Notation

```
% KaTeX inline notation
Inline notation: \\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\\)
```

\\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\\)

### Block Notation

```
% KaTeX block notation
$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$
```


$$ \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } } $$

## Common Formulas

**Perimeter**
$$ \begin{align}
Square: P &= 4a \\\
Rectangle: P &= 2(l+w)
\end{align} $$

**Circumference**
$$\begin{align} 
Circle: C = 2 \pi r 
\end{align}$$

**Area**
$$\begin{align}
Square: A &= a^2 \\\
Rectangle: A &= lw \\\
Triangle: A &= \frac{bh}{2} \\\
Trapezoid: A &= \frac{(b^1 + b^2)h}{2} \\\
Circle: A &= \pi r^2
\end{align}$$

**Surface Area**
$$\begin{align}
Cube: SA &= 6a^2 \\\
Cylinder: SA &= 2\pi r(r+h) \\\
Cone: SA &= \pi r^2 + \pi rl \\\
Sphere: SA &= 4 \pi r^2
\end{align}$$

**Volume**
$$\begin{align}
Cube: V &= a^3 \\\
Cylinder: V &= \pi r^2h \\\
Cone: V &= \frac{\pi r^2 h}{3} \\\
Sphere: V &= \frac{4\pi r^3}{3}
\end{align}$$