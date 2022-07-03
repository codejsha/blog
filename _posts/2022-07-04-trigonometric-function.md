---
title: Trigonometric Function LaTeX Equations
description: LaTeX of the Trigonometric function expression
layout: post
toc: true
comments: true
categories: [math, latex]
---

## Trigonometric function

### Relationship

$$
\begin{align*}
sin(\theta) &= cos(\frac{\pi}{2} - \theta) = \frac{1}{csc(\theta)} \\
cos(\theta) &= sin(\frac{\pi}{2} - \theta) = \frac{1}{sec(\theta)} \\
tan(\theta) &= \frac{sin(\theta)}{cos(\theta)} = cot(\frac{\pi}{2} - \theta) = \frac{1}{cot(\theta)} \\
cot(\theta) &= \frac{cos(\theta)}{sin(\theta)} = tan(\frac{\pi}{2} - \theta) = \frac{1}{tan(\theta)} \\
sec(\theta) &= csc(\frac{\pi}{2} - \theta) = \frac{1}{cos(\theta)} \\
csc(\theta) &= sec(\frac{\pi}{2} - \theta) = \frac{1}{sin(\theta)}
\end{align*}
$$

```text
sin(\theta) &= cos(\frac{\pi}{2} - \theta) = \frac{1}{csc(\theta)} \\
cos(\theta) &= sin(\frac{\pi}{2} - \theta) = \frac{1}{sec(\theta)} \\
tan(\theta) &= \frac{sin(\theta)}{cos(\theta)} = cot(\frac{\pi}{2} - \theta) = \frac{1}{cot(\theta)} \\
cot(\theta) &= \frac{cos(\theta)}{sin(\theta)} = tan(\frac{\pi}{2} - \theta) = \frac{1}{tan(\theta)} \\
sec(\theta) &= csc(\frac{\pi}{2} - \theta) = \frac{1}{cos(\theta)} \\
csc(\theta) &= sec(\frac{\pi}{2} - \theta) = \frac{1}{sin(\theta)}
```

### Parity

$$
\begin{align*}
sin(-x) &= -sin(x) \\
cos(-x) &= cos(x) \\
tan(-x) &= -tan(x) \\
cot(-x) &= -cot(x) \\
sec(-x) &= sec(x) \\
csc(-x) &= -csc(x)
\end{align*}
$$

### Periods

$$
\begin{align*}
sin(x + 2k\pi) &= sin(x) \\
cos(x + 2k\pi) &= cos(x) \\
tan(x + k\pi) &= tan(x) \\
cot(x + k\pi) &= cot(x) \\
sec(x + 2k\pi) &= sec(x) \\
csc(x + 2k\pi) &= csc(x)
\end{align*}
$$

### Pythagorean theorem

$$
\begin{align*}
& sin^2(\theta) + cos^2(\theta) = 1 \\
& tan^2(\theta) + 1 = sec^2(\theta) \\
& 1 + cot^2(\theta) = csc^2(\theta)
\end{align*}
$$

```text
& sin^2(\theta) + cos^2(\theta) = 1 \\
& tan^2(\theta) + 1 = sec^2(\theta) \\
& 1 + cot^2(\theta) = csc^2(\theta)
```

### Sum and difference

$$
\begin{align*}
sin(x + y) &= sin(x)cos(y) + cos(x)sin(y) \\
cos(x + y) &= cos(x)cos(y) - sin(x)sin(y) \\
tan(x + y) &= \frac{tan(x) + tan(y)}{1 - tan(x)tan(y)}
\end{align*}
$$

```text
sin(x + y) &= sin(x)cos(y) + cos(x)sin(y) \\
cos(x + y) &= cos(x)cos(y) - sin(x)sin(y) \\
tan(x + y) &= \frac{tan(x) + tan(y)}{1 - tan(x)tan(y)}
```

$$
\begin{align*}
sin(x - y) &= sin(x)cos(y) - cos(x)sin(y) \\
cos(x - y) &= cos(x)cos(y) + sin(x)sin(y) \\
tan(x - y) &= \frac{tan(x) - tan(y)}{1 + tan(x)tan(y)}
\end{align*}
$$

```text
sin(x - y) &= sin(x)cos(y) - cos(x)sin(y) \\
cos(x - y) &= cos(x)cos(y) + sin(x)sin(y) \\
tan(x - y) &= \frac{tan(x) - tan(y)}{1 + tan(x)tan(y)}
```

### Double angle

$$
\begin{align*}
sin(2x) &= 2sin(x)cos(x) = \frac{2tan(x)}{1 + tan^2(x)} \\
cos(2x) &= cos^2(x) - sin^2(x) = 2cos^2(x) - 1 = 1 - 2sin^2(x) = \frac{1 - tan^2(x)}{1 + tan^2(x)} \\
tan(2x) &= \frac{2tan(x)}{1 -tan^2(x)}
\end{align*}
$$

```text
sin(2x) &= 2sin(x)cos(x) = \frac{2tan(x)}{1 + tan^2(x)} \\
cos(2x) &= cos^2(x) - sin^2(x) = 2cos^2(x) - 1 = 1 - 2sin^2(x) = \frac{1 - tan^2(x)}{1 + tan^2(x)} \\
tan(2x) &= \frac{2tan(x)}{1 -tan^2(x)}
```

### Half angle

$$
\begin{align*}
sin^2(x) &= \frac{1 - cos2(x)}{2} \\
cos^2(x) &= \frac{1 + cos2(x)}{2}
\end{align*}
$$

```text
sin^2(x) &= \frac{1 - cos2(x)}{2} \\
cos^2(x) &= \frac{1 + cos2(x)}{2}
```

### Product

$$
\begin{align*}
sin(x)cos(y) &= \frac{1}{2}[sin(x + y) + sin(x - y)] \\
cos(x)cos(y) &= \frac{1}{2}[cos(x + y) + cos(x - y)] \\
sin(x)sin(y) &= \frac{1}{2}[cos(x - y) - cos(x + y)]
\end{align*}
$$

```text
sin(x)cos(y) &= \frac{1}{2}[sin(x + y) + sin(x - y)] \\
cos(x)cos(y) &= \frac{1}{2}[cos(x + y) + cos(x - y)] \\
sin(x)sin(y) &= \frac{1}{2}[cos(x - y) - cos(x + y)]
```
