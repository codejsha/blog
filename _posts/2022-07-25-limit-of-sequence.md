---
title: Limit of sequence LaTeX Equations
description: LaTeX of the limit of a sequence
layout: post
toc: true
comments: true
categories: [math, latex]
---

## Convergence and divergence of sequence

$$
\lim_{n\to\infty} a_n = L
$$

if $a_n$ exists, then sequence is convergent, otherwise divergent

```text
\lim_{n\to\infty} a_n = L
```

## Properties

if $a_n$ and $b_n$ are convergent sequence and c is constant, then:

$$
\begin{align*}
& \lim_{n\to\infty}c = c \\
& \lim_{n\to\infty}ca_n = c\lim_{n\to\infty}a_n \\
& \lim_{n\to\infty}({a_n + b_n}) = \lim_{n\to\infty}a_n + \lim_{n\to\infty}b_n \\
& \lim_{n\to\infty}({a_n - b_n}) = \lim_{n\to\infty}a_n - \lim_{n\to\infty}b_n \\
& \lim_{n\to\infty}a_nb_n = \lim_{n\to\infty}a_n\lim_{n\to\infty}b_n \\
& \lim_{n\to\infty}\frac{a_n}{b_n} = \frac{\lim_{n\to\infty}a_n}{\lim_{n\to\infty}b_n}
\end{align*}
$$

```text
& \lim_{n\to\infty}c = c \\
& \lim_{n\to\infty}ca_n = c\lim_{n\to\infty}a_n \\
& \lim_{n\to\infty}({a_n + b_n}) = \lim_{n\to\infty}a_n + \lim_{n\to\infty}b_n \\
& \lim_{n\to\infty}({a_n - b_n}) = \lim_{n\to\infty}a_n - \lim_{n\to\infty}b_n \\
& \lim_{n\to\infty}a_nb_n = \lim_{n\to\infty}a_n\lim_{n\to\infty}b_n \\
& \lim_{n\to\infty}\frac{a_n}{b_n} = \frac{\lim_{n\to\infty}a_n}{\lim_{n\to\infty}b_n}
```

## Geometric progression

geometric progression is convergent or divergent according to the range of value of common ratio $r$:

$$
\begin{align*}
& \text{if r > 1, then:} & \lim_{n\to\infty}r^n &= \infty & (divergence) \\
& \text{if r = 1, then:} & \lim_{n\to\infty}r^n &= 1 & (convergence) \\
& \text{if -1 < r < 1, then:} & \lim_{n\to\infty}r^n &= 0 & (convergence)\\
& \text{if r < -1, then:} & \lim_{n\to\infty}r^n &= vibration & (divergence)
\end{align*}
$$

```text
& \text{if r > 1, then:} & \lim_{n\to\infty}r^n &= \infty & (divergence) \\
& \text{if r = 1, then:} & \lim_{n\to\infty}r^n &= 1 & (convergence) \\
& \text{if -1 < r < 1, then:} & \lim_{n\to\infty}r^n &= 0 & (convergence)\\
& \text{if r < -1, then:} & \lim_{n\to\infty}r^n &= vibration & (divergence)
```
