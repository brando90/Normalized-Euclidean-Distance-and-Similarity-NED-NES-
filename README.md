# Normalized-Euclidean-Distance-and-Similarity

An implementation of [Normalized Euclidean Distance/Similiarty](https://stats.stackexchange.com/questions/136232/definition-of-normalized-euclidean-distance)

```
NED^2(u,v) = 0.5 * var(u-v) / var(u) + var(v) + eps
```

This function is very useful when used as a loss because it normalizes regressions tasks using the variance of the predicted and data set values (e.g. var(y_pred) and var(y_target)).
It has the advantage over the cosine function in the the angle between two a batch of predictions and a batch of target values is arguably a unnatural comparison.

## Citation
If you use this implementation in your research consider citing:

```
@software{brando2021ned,
    author={Brando Miranda},
    title={PyTorch implementation of Normalized Euclidean Similarity},
    url={https://github.com/brando90/Normalized-Euclidean-Distance-and-Similarity},
    year={2021}
}
```
