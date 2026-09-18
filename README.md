# Project-1

# Project 1 – TODO

Internal checklist for the project.

## General

* [ ] Set up project structure
* [ ] Decide how to split tasks
* [ ] Clean up notebook/code before submission
* [ ] Make sure results can be reproduced

## a) OLS

* [ ] Generate data
* [ ] Create design matrix
* [ ] Train/test split
* [ ] Implement OLS
* [ ] Scaling/centering
* [ ] Calculate MSE
* [ ] Calculate R²
* [ ] Test different polynomial degrees
* [ ] Test different numbers of data points
* [ ] Test different noise levels
* [ ] Plot training/test error
* [ ] Plot fitted model
* [ ] Discuss underfitting/overfitting

## b) Ridge

* [ ] Implement Ridge
* [ ] Test different λ values
* [ ] Test different polynomial degrees
* [ ] Calculate MSE/R²
* [ ] Plot results
* [ ] Compare with OLS
* [ ] Look at parameter shrinkage

## c) Bootstrap / Bias-Variance

* [ ] Implement bootstrap
* [ ] Calculate MSE
* [ ] Calculate bias
* [ ] Calculate variance
* [ ] Plot bias-variance tradeoff
* [ ] Test different polynomial degrees
* [ ] Test different dataset sizes
* [ ] Write bias-variance derivation/discussion

## d) Cross-Validation

* [ ] Implement 5-fold CV
* [ ] Implement 10-fold CV
* [ ] OLS with CV
* [ ] Ridge with CV
* [ ] Make sure scaling happens inside each fold
* [ ] Compare CV with bootstrap

## e) Gradient Descent

* [ ] Implement analytical OLS gradient
* [ ] Implement analytical Ridge gradient
* [ ] Implement gradients with JAX
* [ ] Compare analytical and JAX gradients
* [ ] Implement Gradient Descent
* [ ] Test OLS
* [ ] Test Ridge
* [ ] Test different learning rates
* [ ] Investigate convergence
* [ ] Compare with closed-form solution

## f) Optimizers

* [ ] Momentum
* [ ] AdaGrad
* [ ] RMSprop
* [ ] Adam
* [ ] Test with OLS
* [ ] Test with Ridge
* [ ] Compare convergence

## g) Lasso

* [ ] Implement Lasso cost function
* [ ] Handle L1 gradient/subgradient
* [ ] Test `jax.grad(jnp.abs)(0.0)`
* [ ] Implement Lasso with GD
* [ ] Compare with Scikit-Learn Lasso
* [ ] Compare OLS / Ridge / Lasso

## h) SGD

* [ ] Implement SGD
* [ ] Implement mini-batches
* [ ] Implement epochs
* [ ] Implement learning-rate schedule
* [ ] Test different batch sizes
* [ ] Test different learning rates
* [ ] Compare SGD with normal GD

## i) Final Comparison

* [ ] Cross-validation for OLS
* [ ] Cross-validation for Ridge
* [ ] Cross-validation for Lasso
* [ ] Tune polynomial degree
* [ ] Tune λ for Ridge
* [ ] Tune λ for Lasso
* [ ] Create final comparison plots/tables
* [ ] Discuss results

## Report

* [ ] Introduction
* [ ] Theory
* [ ] Methods
* [ ] Results
* [ ] Discussion
* [ ] Conclusion
* [ ] Figures have labels/captions
* [ ] Equations are explained
* [ ] References
* [ ] LLM declaration
* [ ] Link repository
* [ ] Final proofreading

## Git

Create a branch:

```bash
git checkout -b branch-name
```

Make branch available to everyone:

```bash
git push -u origin branch-name
```

Get new branches/changes:

```bash
git fetch
git branch -a
```

Switch branch:

```bash
git checkout branch-name
```

Update current branch:

```bash
git pull
```

Commit and push:

```bash
git add .
git commit -m "what was changed"
git push
```
