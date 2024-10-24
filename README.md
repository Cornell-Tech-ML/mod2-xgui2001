[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

# Task 2.5

Results for model training in run_tensor.py:

* Simple dataset:

<img src="Simple_mod2.png" width="50%">

Hyperparameters:

- Learning rate: 0.1
- Hidden layer size: 2
- Epochs: 500

Training time: 18.5s

* Diag dataset:

<img src="Diag_mod2.png" width="50%">

Hyperparameters:

- Learning rate: 0.1
- Hidden layer size: 2
- Epochs: 500

Training time: 19s

* Split dataset:

<img src="Split_mod2_20.png" width="50%">

Hyperparameters:

- Learning rate: 0.1
- Hidden layer size: 20
- Epochs: 500

Training time: 399 s

* Xor dataset:

<img src="Xor_mod2_20.png" width="50%">

Hyperparameters:

- Learning rate: 0.1
- Hidden layer size: 20
- Epochs: 500

Training time: 413.5s

