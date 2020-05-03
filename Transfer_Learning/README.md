# Transfer Learning


## Target:
#### Use Pretrained ResNet-18 architecture
#### Train last fully connected layer to predict only two classes (ants, bees)
#### Import train and test(val) images from drive 
#### Use StepLR from 'torch.optim.lr_scheduler' to Decay learning rate by a factor 0.1 after every 7 epochs
## Results:
#### Parameters: 11,177,538
#### Best Train Accuracy: 88
####  Best Test Accuracy: 92.81
## Analysis:
####  Good model!
#### No overfitting


## Testing Accuracy

![Testing Accuracy](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Transfer_Learning/test_accuracy.PNG)

## Training Logs

![Logs](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Transfer_Learning/training_logs.PNG)

## Let's test images some random images

![Testing Images](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Transfer_Learning/test_prediction.PNG)
