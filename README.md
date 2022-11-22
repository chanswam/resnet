# Train CIFAR10 with ResNet14
ResNet14 is a variant of ResNet18. It removes layer 14 to 17 of ResNet18.

## Prerequisites
- Python 3.6+
- PyTorch 1.0+

## Training
```
# Full training log corresponding to my report can be found in 
log/res14.pdf

# To verify the result in my report, you can manually resume the training with: 
python main.py --resume --lr=0.00001
```

## Accuracy
93.57% when learning rate=0.0001.