# Train CIFAR10 with ResNet14
ResNet14 is a variant of ResNet18. It removes layer 14 to 17 of ResNet18.

## Prerequisites
- Python 3.6+
- PyTorch 1.0+

## Training
```
# To train from the beginning, start with:
python main.py

# When the test accuracy gets stuck, use ctrl+c to pause the training and resume it with:
python main.py --resume --lr=0.01

# Whenever the test accuracy is stuck, pause and resume with last learning rate divided by 10:
python main.py --resume --lr=0.001

# Full training log corresponding to my report can be found in 
log/res14.pdf

# To verify the result in my report, you can download the whole data folder from my google drive link
https://drive.google.com/drive/folders/15AL-yYwJNIDJhe6wrkWExkKuGrhZNWiC

Cut and paste the data folder to resnet folder, then manually resume the training with: 
python main.py --resume --lr=0.00001
```

## Accuracy
93.57% when learning rate=0.0001.
