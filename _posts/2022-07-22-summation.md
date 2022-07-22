---
title: Summation LaTeX Equations
description: LaTeX of the summation expression
layout: post
toc: true
comments: true
categories: [math, latex]
---

## Notation

$$
\sum_{i=m}^n a_{i} = a_{m} + a_{m+1} + a_{m+2} + \dots + a_{n-1} + a_{n}
$$

## General identities

$$
\begin{align*}
& \sum_{k=m}^n ca_k = c \sum_{k=m}^n a_k \\
& \sum_{k=m}^n (a_k \plusmn b_k) = \sum_{k=m}^n a_k \plusmn \sum_{k=m}^n b_k \\
& \sum_{k=m}^n a_k = \sum_{k=m+p}^{n+p} a_{k-p} \\
& \sum_{k=m}^n a_k = \sum_{k=m}^{t} a_k + \sum_{k=t+1}^{m} a_k \\
& \sum_{k=m}^n a_k = \sum_{k=0}^{n} a_k - \sum_{k=0}^{m-1} a_k
\end{align*}
$$

```text
& \sum_{k=m}^n ca_k = c \sum_{k=m}^n a_k \\
& \sum_{k=m}^n (a_k \plusmn b_k) = \sum_{k=m}^n a_k \plusmn \sum_{k=m}^n b_k \\
& \sum_{k=m}^n a_k = \sum_{k=m+p}^{n+p} a_{k-p} \\
& \sum_{k=m}^n a_k = \sum_{k=m}^{t} a_k + \sum_{k=t+1}^{m} a_k \\
& \sum_{k=m}^n a_k = \sum_{k=0}^{n} a_k - \sum_{k=0}^{m-1} a_k
```

## Powers and logarithm

$$
\begin{align*}
& \sum_{k=1}^n 1 = n \\
& \sum_{k=1}^n c = nc \\
& \sum_{k=1}^n (2k - 1) = n^2 \\
& \sum_{k=1}^n \log_{}{k} = \log_{}{k!} \\
& \sum_{k=1}^n k = \frac{n(n + 1)}{2} \\
& \sum_{k=1}^n k^2 = \frac{n(n + 1)(2n + 1)}{6} \\
& \sum_{k=1}^n k^3 = \left( \frac{n(n + 1)}{2} \right)^2 = \frac{n^2(n + 1)^2}{4}
\end{align*}
$$

```text
& \sum_{k=1}^n 1 = n \\
& \sum_{k=1}^n c = nc \\
& \sum_{k=1}^n (2k - 1) = n^2 \\
& \sum_{k=1}^n \log_{}{k} = \log_{}{k!} \\
& \sum_{k=1}^n k = \frac{n(n + 1)}{2} \\
& \sum_{k=1}^n k^2 = \frac{n(n + 1)(2n + 1)}{6} \\
& \sum_{k=1}^n k^3 = \left( \frac{n(n + 1)}{2} \right)^2 = \frac{n^2(n + 1)^2}{4}
```

## Exponents

$$
\begin{align*}
& \sum_{k=0}^n x^k = \frac{x^{n+1} - 1}{x - 1} \\
& \sum_{k=0}^{\infty} x^k = \frac{1}{1 - x}, \quad (\mid x \mid < 1) \\
& \sum_{k=0}^{\infty} kx^k = \frac{x}{(1 - x)^2}, \quad (\mid x \mid < 1) \\
& \sum_{k=1}^{n} \frac{1}{k} = 1 + \frac{1}{x} + \frac{1}{x^2} + \frac{1}{x^3} + \cdots + \frac{1}{x^n}
\end{align*}
$$

```text
& \sum_{k=0}^n x^k = \frac{x^{n+1} - 1}{x - 1} \\
& \sum_{k=0}^{\infty} x^k = \frac{1}{1 - x}, \quad (\mid x \mid < 1) \\
& \sum_{k=0}^{\infty} kx^k = \frac{x}{(1 - x)^2}, \quad (\mid x \mid < 1) \\
& \sum_{k=1}^{n} \frac{1}{k} = 1 + \frac{1}{x} + \frac{1}{x^2} + \frac{1}{x^3} + \cdots + \frac{1}{x^n}
```

## Telescopes

$$
\begin{align*}
& \sum_{k=1}^n (a_k - a_{k-1}) = a_n - a_0 \\
& \sum_{k=0}^n (a_k - a_{k+1}) = a_0 - a_n \\
& \sum_{k=1}^{n-1} \frac{1}{k(k + 1)} = 1 - \frac{1}{n}
\end{align*}
$$

```text
& \sum_{k=1}^n (a_k - a_{k-1}) = a_n - a_0 \\
& \sum_{k=0}^n (a_k - a_{k+1}) = a_0 - a_n \\
& \sum_{k=1}^{n-1} \frac{1}{k(k + 1)} = 1 - \frac{1}{n}
```
