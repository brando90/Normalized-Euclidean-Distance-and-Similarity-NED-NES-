# Normalized-Euclidean-Distance-and-Similarity (NED & NES)

An implementation of [Normalized Euclidean Distance/Similiarty](https://stats.stackexchange.com/questions/136232/definition-of-normalized-euclidean-distance)

```
NED^2(u,v) = 0.5 * var(u-v) / var(u) + var(v) + eps
```

This function is very useful when used as a loss because it normalizes regressions tasks using the variance of the predicted and data set values (e.g. var(y_pred) and var(y_target)).
The main advantage over R^2 is that it is symmetric and guranteed to be bounded between 0-1 but it is less interpretable (e.g. what does chance mean here? But R^2 has a clear meaning for that i.e. predicting the average labe)

## Citation
If you use this implementation consider please citing us:

```
@software{brando2021ned,
    author={Brando Miranda},
    title={PyTorch implementation of Normalized Euclidean Similarity},
    url={https://github.com/brando90/Normalized-Euclidean-Distance-and-Similarity},
    year={2021}
}
```
