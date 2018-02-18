# Skewness-Process

This is an algorithm to find an analytic function for given real values.

Such that values transfered by this function has zero-mean, unit standard deviation, zero skewness and order-preserve.

--

# Introduction

For sample $\{x_i\}_{i=1, ... , n} \subset \mathbb{R}$ with positive third centeral moment

$$ \sum{(x_i - \overline{x})^3} > 0 $$

where $\overline{x}$ is the mean of sample $\frac{\sum{(x_i)}}{n} $.

We can construct a monotone increasing analytic function (order-preserve)

$$ f:\mathbb{R} \rightarrow \mathbb{R} $$

$$ f(x) = a*(\ln(x+k) - b) $$

such that $\{y_i\}$, with $y_i = f(x_i)$, has zero-mean, unit standard deviation and zero skewness

$$ \sum{y_i} = 0 $$

$$ \sum{y_i}^2 = 1 $$

$$ \sum{y_i}^3 = 0 $$

moreover, $a, b, k$ above are unique



For case negative third centeral moment, apply this process to $\{-x_i\}$, and reverse $\{y_i\}$ finally.
