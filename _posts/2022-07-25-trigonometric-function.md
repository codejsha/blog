---
title: Trigonometric Function LaTeX Equations
description: LaTeX of the Trigonometric functions
layout: post
toc: true
comments: true
image: images/fastpages_posts/math/trig-function-diagram.svg
categories: [math, latex]
---

## Trigonometric function

![]({{ site.baseurl }}/images/fastpages_posts/math/trig-function-diagram.svg "Plot of the six trigonometric functions, the unit circle, and a line for the angle θ = 0.7 radians. Trigonometric functions - Wikipedia (https://en.wikipedia.org/wiki/Trigonometric_functions)")

$$
\begin{align*}
\sin{\theta} &= \frac{y}{r} \\
\cos{\theta} &= \frac{x}{r} \\
\tan{\theta} &= \frac{y}{x} \quad (x \neq 0) \\
\csc{\theta} &= \frac{r}{y} \quad (y \neq 0) \\
\sec{\theta} &= \frac{r}{x} \quad (x \neq 0) \\
\cot{\theta} &= \frac{x}{y} \quad (y \neq 0)
\end{align*}
$$

### Relationship

$$
\begin{align*}
\sin\theta &= \cos \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\csc\theta} \\
\cos\theta &= \sin \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\sec\theta} \\
\tan\theta &= \frac{\sin\theta}{\cos\theta} = \cot \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\cot\theta} \\
\cot\theta &= \frac{\cos\theta}{\sin\theta} = \tan \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\tan\theta} \\
\sec\theta &= \csc \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\cos\theta} \\
\csc\theta &= \sec \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\sin\theta}
\end{align*}
$$

```text
\sin\theta &= \cos \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\csc\theta} \\
\cos\theta &= \sin \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\sec\theta} \\
\tan\theta &= \frac{\sin\theta}{\cos\theta} = \cot \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\cot\theta} \\
\cot\theta &= \frac{\cos\theta}{\sin\theta} = \tan \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\tan\theta} \\
\sec\theta &= \csc \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\cos\theta} \\
\csc\theta &= \sec \left( \frac{\pi}{2} - \theta \right) = \frac{1}{\sin\theta}
```

### Parity

$$
\begin{align*}
\sin{(-x)} &= -\sin{x} \\
\cos{(-x)} &= \cos{x} \\
\tan{(-x)} &= -\tan{x} \\
\cot{(-x)} &= -\cot{x} \\
\sec{(-x)} &= \sec{x} \\
\csc{(-x)} &= -\csc{x}
\end{align*}
$$

### Periods

$$
\begin{align*}
\sin{(x + 2k\pi)} &= \sin{x} \\
\cos{(x + 2k\pi)} &= \cos{x} \\
\tan{(x + k\pi)} &= \tan{x} \\
\cot{(x + k\pi)} &= \cot{x} \\
\sec{(x + 2k\pi)} &= \sec{x} \\
\csc{(x + 2k\pi)} &= \csc{x}
\end{align*}
$$

### Pythagorean theorem

$$
\begin{align*}
& \sin^2{\theta} + \cos^2{\theta} = 1 \\
& \tan^2{\theta} + 1 = \sec^2{\theta} \\
& 1 + \cot^2{\theta} = \csc^2{\theta}
\end{align*}
$$

```text
& \sin^2{\theta} + \cos^2{\theta} = 1 \\
& \tan^2{\theta} + 1 = \sec^2{\theta} \\
& 1 + \cot^2{\theta} = \csc^2{\theta}
```

### Sum and difference

$$
\begin{align*}
\sin{(x + y)} &= \sin{x}\cos{y} + \cos{x}\sin{y} \\
\sin{(x - y)} &= \sin{x}\cos{y} - \cos{x}\sin{y} \\
\cos{(x + y)} &= \cos{x}\cos{y} - \sin{x}\sin{y} \\
\cos{(x - y)} &= \cos{x}\cos{y} + \sin{x}\sin{y} \\
\tan{(x + y)} &= \frac{\tan{x} + \tan{y}}{1 - \tan{x} \tan{y}} \\
\tan{(x - y)} &= \frac{\tan{x} - \tan{y}}{1 + \tan{x} \tan{y}}
\end{align*}
$$

```text
\sin{(x + y)} &= \sin{x}\cos{y} + \cos{x}\sin{y} \\
\sin{(x - y)} &= \sin{x}\cos{y} - \cos{x}\sin{y} \\
\cos{(x + y)} &= \cos{x}\cos{y} - \sin{x}\sin{y} \\
\cos{(x - y)} &= \cos{x}\cos{y} + \sin{x}\sin{y} \\
\tan{(x + y)} &= \frac{\tan{x} + \tan{y}}{1 - \tan{x} \tan{y}} \\
\tan{(x - y)} &= \frac{\tan{x} - \tan{y}}{1 + \tan{x} \tan{y}}
```

### Double angle

$$
\begin{align*}
\sin{2x} &= 2\sin{x}\cos{x} \\
         &= \frac{2\tan{x}}{1 + \tan^2{x}} \\
\cos{2x} &= \cos^2{x} - \sin^2{x} \\
         &= 2\cos^2{x} - 1 \\
         &= 1 - 2\sin^2{x} \\
         &= \frac{1 - \tan^2{x}}{1 + \tan^2{x}} \\
\tan{2x} &= \frac{2\tan{x}}{1 -\tan^2{x}}
\end{align*}
$$

```text
\sin{2x} &= 2\sin{x}\cos{x} \\
         &= \frac{2\tan{x}}{1 + \tan^2{x}} \\
\cos{2x} &= \cos^2{x} - \sin^2{x} \\
         &= 2\cos^2{x} - 1 \\
         &= 1 - 2\sin^2{x} \\
         &= \frac{1 - \tan^2{x}}{1 + \tan^2{x}} \\
\tan{2x} &= \frac{2\tan{x}}{1 -\tan^2{x}}
```

### Half angle

$$
\begin{align*}
\sin^2{x} &= \frac{1 - \cos{2x}}{2} \\
\cos^2{x} &= \frac{1 + \cos{2x}}{2}
\end{align*}
$$

```text
\sin^2{x} &= \frac{1 - \cos{2x}}{2} \\
\cos^2{x} &= \frac{1 + \cos{2x}}{2}
```

### Product

$$
\begin{align*}
\sin{x}\cos{y} &= \frac{1}{2}[\sin(x + y) + \sin(x - y)] \\
\cos{x}\cos{y} &= \frac{1}{2}[\cos(x + y) + \cos(x - y)] \\
\sin{x}\sin{y} &= \frac{1}{2}[\cos(x - y) - \cos(x + y)]
\end{align*}
$$

```text
\sin{x}\cos{y} &= \frac{1}{2}[\sin(x + y) + \sin(x - y)] \\
\cos{x}\cos{y} &= \frac{1}{2}[\cos(x + y) + \cos(x - y)] \\
\sin{x}\sin{y} &= \frac{1}{2}[\cos(x - y) - \cos(x + y)]
```
