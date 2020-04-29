# Mini ResNet From Scratch


## Target:
## Create Mini ResNet architecture of 16 layer
## Save model after training to Googlr Drive
## Apply Image augmentation (transforms.Pad(4),
                                 transforms.RandomHorizontalFlip(),
                                 transforms.RandomCrop(32),
                                 )
## Decay the learning rate by a factor of 0.5 every 20 epochs
# Results:
## Parameters: 195,738
## Best Train Accuracy: 91.340
## Best Test Accuracy: 86.38
# Analysis:
## Good model!
## We see some over-fitting

## ResNet Architecture

![Mini ResNet Architecture](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Mini_ResNet16_From_Scratch/architecture.png)

## Training Logs

![Logs](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Mini_ResNet16_From_Scratch/training_log.PNG)

## Let's test images some random images

![Testing Images](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Mini_ResNet16_From_Scratch/test_image.PNG)
