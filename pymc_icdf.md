
## References
- Issue #6612:  https://github.com/pymc-devs/pymc/issues/6612
- `def check_icdf_value` is in this file: [dist_math](https://github.com/pymc-devs/pymc/blob/main/pymc/distributions/dist_math.py)

## Workflow
1. Determine if the distribution is `Continous` or `Discrete`
2. The files that have the code are here:  
    - `Continous` distributions:  https://github.com/pymc-devs/pymc/blob/main/pymc/distributions/continuous.py
    - `Discrete` distributions: https://github.com/pymc-devs/pymc/blob/main/pymc/distributions/discrete.py



## Continuous: Example
There is a class for each distribution:  
```
class Normal(Continuous):
    r"""
    Univariate normal log-likelihood.
    The pdf of this distribution is
    .. math::
       f(x \mid \mu, \tau) =
           \sqrt{\frac{\tau}{2\pi}}
           \exp\left\{ -\frac{\tau}{2} (x-\mu)^2 \right\}
```

Within this class there is   :

```
    def icdf(value, mu, sigma):
        res = mu + sigma * -np.sqrt(2.0) * pt.erfcinv(2 * value)
        res = check_icdf_value(res, value)
        return check_icdf_parameters(
            res,
            sigma > 0,
            msg="sigma > 0",
        )
```
