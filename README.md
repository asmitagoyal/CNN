# CNN

1. First created **CNN model** with training accuracy = 0.84 and validation accuracy = 0.45 with epoch =20 and training size= 1792 and validation size = 447
2. As the model was overfitting therefore used **dropouts** layer with 25% zeros, training accuracy = 0.53, validation=0.52

  a. saw a huge difference in validation accuracy
  b. overfitting got resolved
  c. training and validation accuracy dont have a huge gap now
3. Created more images using **Augmentor** library to rebalance class

Modification can be done with addition of 
a. different layer
b. changing epoch size
