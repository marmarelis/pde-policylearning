# pde-observers

1. First run the following to preprocess data (for efficient running and debugging):

```
python lib/mat2npy.py
```


2. Then run to train the supervised pde observers:

```
python run_pde_observers.py
# rno
python run_pde_observers.py --
```


3. Run the controller via:

```
python run_control.py
```