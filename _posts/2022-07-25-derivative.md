---
title: Derivative LaTeX Equations
description: LaTeX of derivatives
layout: post
toc: true
comments: true
categories: [math, latex]
---

## Tangent line

$$
\begin{align*}
m &= \lim_{x \to a} \frac{f(x) - f(a)}{x - a} \\
  &= \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}
\end{align*}
$$

```text
m &= \lim_{x \to a} \frac{f(x) - f(a)}{x - a} \\
  &= \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}
```


## Rate of change

### Average rate of change

$$
\frac{\Delta y}{\Delta x} = \frac{f(x_2) - f(x_1)}{x_2 - x_1}
$$

```text
\frac{\Delta y}{\Delta x} = \frac{f(x_2) - f(x_1)}{x_2 - x_1}
```

### Instantaneous rate of change

$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{x_2 \to x_1} \frac{f(x_2) - f(x_1)}{x_2 - x_1}
$$

```text
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{x_2 \to x_1} \frac{f(x_2) - f(x_1)}{x_2 - x_1}
```

## Derivative

$$
f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}
$$

```text
f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}
```

$$
\begin{align*}
& \text{derivative:} & f'(x) &= y' = \frac{dy}{dx} = \frac{df}{dx} = \frac{d}{dx}f(x) \\
& \text{second derivative:} & f''(x) &= \frac{d}{dx} \frac{dy}{dx} = \frac{d^2y}{dx^2} \\
& \text{third derivative:} & f'''(x) &= \frac{d}{dx} \left( \frac{d^2y}{dx^2} \right) = \frac{d^3y}{dx^3}
\end{align*}
$$

```text
& \text{derivative:} & f'(x) &= y' = \frac{dy}{dx} = \frac{df}{dx} = \frac{d}{dx}f(x) \\
& \text{second derivative:} & f''(x) &= \frac{d}{dx} \frac{dy}{dx} = \frac{d^2y}{dx^2} \\
& \text{third derivative:} & f'''(x) &= \frac{d}{dx} \left( \frac{d^2y}{dx^2} \right) = \frac{d^3y}{dx^3}
```

## Differentiation formulas

$$
\frac{d}{dx} x^n = nx^{n-1}
$$

```text
\frac{d}{dx} x^n = nx^{n-1}
```

$$
\begin{align*}
\frac{d}{dx} [cf(x)] &= c \frac{d}{dx} f(x) \\
                     &= cf'(x)
\end{align*}
$$

```text
\frac{d}{dx} [cf(x)] &= c \frac{d}{dx} f(x) \\
                     &= cf'(x)
```

$$
\begin{align*}
\frac{d}{dx} [f(x) + g(x)] &= \frac{d}{dx} f(x) + \frac{d}{dx} g(x) \\
                           &= f'(x) + g'(x) \\
\frac{d}{dx} [f(x) - g(x)] &= \frac{d}{dx} f(x) - \frac{d}{dx} g(x) \\
                           &= f'(x) - g'(x)
\end{align*}
$$

```text
\frac{d}{dx} [f(x) + g(x)] &= \frac{d}{dx} f(x) + \frac{d}{dx} g(x) \\
                           &= f'(x) + g'(x)
\frac{d}{dx} [f(x) - g(x)] &= \frac{d}{dx} f(x) - \frac{d}{dx} g(x) \\
                           &= f'(x) - g'(x)
```

$$
\begin{align*}
\frac{d}{dx} [f(x) g(x)] &= f(x) \frac{d}{dx} g(x) + g(x) \frac{d}{dx} f(x) \\
                         &= f(x)g'(x) + g(x)f'(x) \\
\frac{d}{dx} \left[ \frac{f(x)}{g(x)} \right] &= \frac{g(x) \frac{d}{dx} [f(x)] - f(x) \frac{d}{dx} [g(x)]}{[g(x)]^2} \\
                                              &= \frac{g(x)f'(x) - f(x)g'(x)}{[g(x)]^2}
\end{align*}
$$

```text
\frac{d}{dx} [f(x) g(x)] &= f(x) \frac{d}{dx} g(x) + g(x) \frac{d}{dx} f(x) \\
                         &= f(x)g'(x) + g(x)f'(x)
\frac{d}{dx} \left[ \frac{f(x)}{g(x)} \right] &= \frac{g(x) \frac{d}{dx} [f(x)] - f(x) \frac{d}{dx} [g(x)]}{[g(x)]^2} \\
                                              &= \frac{g(x)f'(x) - f(x)g'(x)}{[g(x)]^2}
```

## Derivatives of trigonometric functions

$$
\begin{align*}
\frac{d}{dx} (\sin{x}) &= \cos{x} \\
\frac{d}{dx} (\cos{x}) &= -\sin{x} \\
\frac{d}{dx} (\tan{x}) &= \sec^2{x} \\
\frac{d}{dx} (\sec{x}) &= \sec{x}\tan{x} \\
\frac{d}{dx} (\csc{x}) &= -\csc{x}\cot{x} \\
\frac{d}{dx} (\cot{x}) &= -\csc^2{x}
\end{align*}
$$

```text
\frac{d}{dx} (\sin{x}) &= \cos{x} \\
\frac{d}{dx} (\cos{x}) &= -\sin{x} \\
\frac{d}{dx} (\tan{x}) &= \sec^2{x} \\
\frac{d}{dx} (\sec{x}) &= \sec{x}\tan{x} \\
\frac{d}{dx} (\csc{x}) &= -\csc{x}\cot{x} \\
\frac{d}{dx} (\cot{x}) &= -\csc^2{x}
```

## Derivatives of composite functions

$$
\begin{align*}
& y' = f'(g(x)) \cdot g'(x) \\
& (f \circ g)'(x) = f'(g(x)) \cdot g'(x) \\
& \frac{dy}{dx} = \frac{dy}{du} \frac{du}{dx}\\
\end{align*}
$$

```text
& y' = f'(g(x)) \cdot g'(x) \\
& (f \circ g)'(x) = f'(g(x)) \cdot g'(x) \\
& \frac{dy}{dx} = \frac{dy}{du} \frac{du}{dx}\\
```
