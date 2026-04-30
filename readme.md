# On the Tightness and Computational Tractability of Higher-Dimensional Confidence Sequences

Paper implementation.

To reproduce the experiments, run:

```
python run_experiments_async.py
```

In the script, set `small_scale=True` to reproduce the small-scale Bounded UP experiment from the appendix. For the experiments from the main text, set `small_scale=False`.

The results will be logged into the `logs` directory. 

- Running `ab_testing.py` (directly from that directory) reproduces the A/B Web Metrics experiment.
- The scripts under `adaptive_sample/conf_sequences/model_comparison` can be run to 1) train the classifiers and 2) evaluate the model comparison experiments.