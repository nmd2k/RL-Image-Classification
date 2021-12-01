
## Install
To install dependencies, run:
```shell
pip install -r requirements.txt
```

## How to run
The `train.py` take 2 arguments as input: `--batch_size` and `--iters`

Run the training process by `run_train.sh`:
```shell
chmod +x ./run_train.sh
./run_train.sh
```

or by shell command
```shell
python train.py --batch_size <number_of_bz> --iters <number_of_iters>
#               --batch_size 8              --iters 1000                    
#               --batch_size 16             --iters 10000                    
#               --batch_size 32             --iters 100000                    
```


> # CS 165 Project
> ### Reinforcement Learning for Image Classification
> Bhairav Chidambaram, Rohan Choudhury, Connor Soohoo (advised by Hoang Le)

> ## Results
> See final_report.pdf for a summary of the experiment, plots, and discussion of the results.

## References
https://arxiv.org/pdf/1811.06032.pdf

