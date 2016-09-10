# Assignment-Solution

## Requirements

- Python 2.7
- Tensorflow > 0.8
- Numpy


## To run
./train_cnn.py

## Evaluating

```bash
./eval.py --checkpoint_dir="./cnn_run/1473457426/checkpoints/"
```

Replace the checkpoint dir with the output from the training. Replace the test data in data folder to test on a new data. The file should have test labels in the first column and question in the second column seperated by a comma. Eg: What , 'What is your name ? '
A label file will be created in the Assignment-Solution folder called test.txt which will have the corresponding labels.
