# ML_TensorFlow_Flowers

Convolutional Neural Network (CNN) based on TensorFlow/Keras for classifying five types of flowers from the Flower Photos dataset (daisies, dandelions, roses, sunflowers, and tulips). Throughout the development process, I implemented a full training cycle: from data preparation and caching in  180х180 pixel format to mitigating overfitting using augmentation layers (RandomFlip, RandomRotation, RandomContrast) and Dropout regularization. To optimize the process, I integrated EarlyStopping and ReduceLROnPlateau, which resulted in stable accuracy and correct model performance during inference on new images.
DataSet: https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz
