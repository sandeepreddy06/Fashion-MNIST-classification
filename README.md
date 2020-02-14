Fashion MNIST Classification Assignment
### Training
```
python train.py

        --model         # specify model, (FashionSimpleNet, resnet18)
        --patience      # early stopping
        --batch_size    # batch size
        --nepochs       # max epochs
        --nworkers      # number of workers
        --seed          # random seed
        --data          # MNIST or FashionMNIST
```


### Results
|   | FashionSimpleNet | ResNest18 |
| ------------- | ------------- |-----------|
| MNIST  | 0.994  | 0.994|
| FashionMNIST  | 0.923  | 0.920|


