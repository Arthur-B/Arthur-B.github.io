---
layout: page
title: Pi estimate
permalink: /projects/pi-estimate
categories: project
---

## Overview

### Problem definition ###

$$\pi$$ is an irrational number defined as the ratio of a circle's circumference to its diameter.
One way to determine $$\pi$$ is to compare the area of a circle, $$A_{Circle}$$,
to the area of the square, $$A_{Square}$$, enclosing it.

$$
A_{Circle} = \pi r^2\\
A_{Square} = (2r)^2\\
\pi = 4 \times \frac{A_{Circle}}{A_{Square}}
$$

If we can estimate the ratio $$A_{Circle}/A_{Square}$$, then we can determine $$\pi$$.

However, we do not know the precise area of the circle since we do not know $$\pi$$.
The only thing that we know is that a point of coordinates $$(x,y)$$ is inside
a circle of radius $$r$$ if we have

$$
\sqrt{x^2 + y^2} \leq r
$$

So the only thing we can do is check if a point is inside the circle or not.

![](\side-projects\pi-estimate\images\concept.png)

Knowing this we generate points within the circle

$$
\frac{A_{Circle}}{A_{Square}} \approx \frac{Nb points inside}{Total nb of points}
$$

### Monte Carlo method ###

The Monte Carlo method rely on repeated random sampling to obtain numerical results.
For our problem

![](\side-projects\pi-estimate\images\2000.png)

# Results

# Computation cost
