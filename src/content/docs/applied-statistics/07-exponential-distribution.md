---
title: Exponential Distribution
sidebar:
  order: 7
slug: applied-statistics/exponential-distribution
prev: true
next: true
---

Denoted as $\text{Exp}(\lambda)$.

```math
P(x) = \lambda \exp(-\lambda x)
```

Here $\lambda$ is the rate parameter, which represents the mean number of events per unit time. Similar to the rate of failures or a rate of arrivals in [Poisson distribution](https://s2.sahtihyan.dev/methods-of-mathematics/probability/discrete-probablity-distribution/#poisson-distribution).

Can be thought of as an continuous analogue of the [geometric distribution](/applied-statistics/geometric-distribution/). [Memoryless](/applied-statistics/introduction/#memorylessness).

Events must be occurring continuously and independently. Used to model inter-arrival times between completely random events (arrivals/hour), service times (services/minute), lifetime of a product which fails catastrophically (failure rate).

## Properties

### Relation to Poisson Distribution

**If** $X\sim\text{Exp}(\lambda)$ **then** $N \sim \text{Poisson}(\lambda)$. Here $N$ is the number of events that occur in a fixed interval of time. The parameter is same because they describe the same underlying process.

### CDF

```math
F_x(x) = \lambda \int_0^x e^{-\lambda y} \text{d}y = 1 - e^{-\lambda x}
```

### Mean

```math
\mu_x = \frac{1}{\lambda}
```

### Variance

```math
\sigma_x^2 = \frac{1}{\lambda^2}
```

### Percentile

```math
x_{p} = \frac{-1}{\lambda} \ln \left( 1- \frac{p}{100} \right)
```

### Moment Generating Function

```math
M_x(t) = \frac{\lambda}{\lambda - t}
```

## Theorem

$X$ has an exponential distribution **iff**:
- $X$ is a positive continuous r.v. **and**
- $X$ has memoryless property, that is $P(X>s+t | X>s) = P(X>t) \;\text{for all}\; s,t> 0$.
