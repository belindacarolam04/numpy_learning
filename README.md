# NumPy Learning

Hands-on practice repo for learning NumPy — built while preparing for a data science career, with a focus on probability distributions and their connection to real machine learning use cases.

## Notebooks

**Normal_Distribution.ipynb**
- `np.random.normal(loc, scale, size)`
- Understanding `loc` (mean) and `scale` (standard deviation)
- Practice problem: College Mark Analyser — generating marks, calculating average/highest/lowest, filtering students above/below thresholds, pass percentage

**Uniform_Distribution.ipynb**
- `np.random.uniform()`
- Comparing Uniform vs Normal distribution shape (histogram + KDE)

**Other_Distribution.ipynb**
- Binomial Distribution — `np.random.binomial(n, p, size)` — fixed number of trials, two outcomes (e.g. coin toss, exam pass/fail, product inspection)
- Multinomial Distribution — `np.random.multinomial(n, p, size)` — more than two outcomes (e.g. survey responses, dice, grades)
- Poisson Distribution — `np.random.poisson(lam, size)` — events occurring over time/space, understanding lambda as average rate of events
- Exponential Distribution
- Logistic Distribution — `np.random.logistic(loc, scale, size)` — similar to Normal with heavier tails, used in logistic regression, classification, neural network sigmoid activation
- Chi-Square Distribution

**random.ipynb**
- General `np.random` module functions and array generation

**Seaborn.ipynb**
- Visualizing distributions using Seaborn

## Approach

- Each distribution is connected to a real use case, not just the syntax (e.g. Poisson → customer arrivals, website visits per minute; Binomial → coin toss, quality inspection; Logistic → classification problems)
- Concepts are backed by handwritten notes covering definitions, examples, and code before being implemented in notebooks

## Related Repos

- [pandas_learning](https://github.com/belindacarolam04/pandas_learning) — Pandas data manipulation practice on real datasets
