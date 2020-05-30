# Fashion_MNIST
- Image classification using TF.Keras
- Google Colab used for training model

### About Data
- Image dimmensions are 28x28
- There are 10 different classes of images:
  - 0: T-shirt/top;
  - 1: Trouser;
  - 2: Pullover;
  - 3: Dress;
  - 4: Coat;
  - 5: Sandal;
  - 6: Shirt;
  - 7: Sneaker;
  - 8: Bag;
  - 9: Ankle boot.


## PART A
- Basic CNN model applied
- Considerable difference between the training and validation accuracy obsered inferring over-fitting of model on the training data

![alt text](https://github.com/ravigupta5/Fashion_MNIST/blob/master/cnn_acc_loss.PNG?raw=true)

## PART B
- Attempting Dropout with DNN 
- Improve validation and test accuracy obtainded

![alt text](https://github.com/ravigupta5/Fashion_MNIST/blob/master/dnn_acc_loss.PNG?raw=true)

![alt text](https://github.com/ravigupta5/Fashion_MNIST/blob/master/comparison.PNG?raw=true)

## PART C 
- Analysing the influence of learning rate on results
- Learning rate of 0.001 found most appropriate
- Batch size has no significant impact

![alt text](https://github.com/ravigupta5/Fashion_MNIST/blob/master/learning_rates.PNG?raw=true)
