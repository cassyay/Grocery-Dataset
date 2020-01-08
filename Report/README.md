
## Overview 
### Custom dataset: 
- Downloaded datasets and unzipped files
- Separated Freiberg Grocery Set images into train and test sets  
- Combined both datasets into train and test folders 
- Renamed image names and folder names for both datasets
- Created custom Dataset to override __getitem__ and __len__
- Transformed and loaded images so they are prepared

### Algorithm: 
- Used pre-trained network, ResNet18, for transfer learning
- Froze final layer and created new layer
- Ran through training 
- Fine-tuned final layer
- Ran through training to measure improvement



## Resources 


### Creating a custom dataset: 

- [Towards Data Science: Building efficient custom datasets in pytorch](https://towardsdatascience.com/building-efficient-custom-datasets-in-pytorch-2563b946fd9f)

- [StackOverflow: custom based datasets](https://stackoverflow.com/questions/51577282/how-do-i-load-custom-image-based-datasets-into-pytorch-for-use-with-a-cnn)
- [Pytorch: Pytorch with examples](https://pytorch.org/tutorials/beginner/pytorch_with_examples.html)

- [Pytorch: Pytorch tutorial](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html)

- [Pytorch: Pytorch data loading tutorial](https://pytorch.org/tutorials/beginner/data_loading_tutorial.html)

- [Medium: classification using pytorch tutorial](https://medium.com/@uijaz59/dog-breed-classification-using-pytorch-207cf27c2031)

- [Medium: writing a dataloader for a custom dataset (neural network)](https://medium.com/analytics-vidhya/writing-a-custom-dataloader-for-a-simple-neural-network-in-pytorch-a310bea680af)

- [Naadi speaks: custom dataset tips and tricks](https://naadispeaks.wordpress.com/2019/10/08/pytorch-custom-dataset-tips-and-tricks/)

- [Github: pytorch custom dataset examples](https://github.com/utkuozbulak/pytorch-custom-dataset-examples/blob/master/README.md)

### Finding a CNN:

- [Pytorch: Training a classifier](https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html) 

- [Medium: Deep learning for image classification with pytorch](https://towardsdatascience.com/convolutional-neural-network-for-image-classification-with-implementation-on-python-using-pytorch-7b88342c9ca9)

- [Medium: How to train an image classifier in pytorch...](https://towardsdatascience.com/how-to-train-an-image-classifier-in-pytorch-and-use-it-to-perform-basic-inference-on-single-images-99465a1e9bf5)

- [Deep representation learning with target coding](http://personal.ie.cuhk.edu.hk/~ccloy/project_target_code/index.html)

- [Fruits 360 results writeup](https://github.com/Horea94/Fruit-Images-Dataset/tree/master/papers)

- [Stack abuse: Image classification with transfer learning](https://stackabuse.com/image-classification-with-transfer-learning-and-pytorch/) 

- [Learn OpenCV: Pytorch for beginners: image classification using pre-trained models](https://www.learnopencv.com/pytorch-for-beginners-image-classification-using-pre-trained-models/) 

- [Medium: Apples and oranges a machine learning classifier](https://medium.com/modeldepot/apples-oranges-a-machine-learning-classifier-baf549451502)

- [Domino Data Lab: Benchmarking predictive models](https://blog.dominodatalab.com/benchmarking-predictive-models/)

- [Fruit recognition from images using deep learning](https://www.researchgate.net/publication/321475443_Fruit_recognition_from_images_using_deep_learning)

- [Free Code Camp: How to build an image classifier with greater than 97% accuracy](https://www.freecodecamp.org/news/how-to-build-the-best-image-classifier-3c72010b3d55/)

- [Medium: Overview of different optimizers for neural networks](https://www.freecodecamp.org/news/how-to-build-the-best-image-classifier-3c72010b3d55/)

- [Machine Learning Mastey: How to cohose loss functions](https://www.freecodecamp.org/news/how-to-build-the-best-image-classifier-3c72010b3d55/)

- [Kaggle: Fruits-360 Transfer learning using Keras and ResNet-50](https://www.kaggle.com/amadeus1996/fruits-360-transfer-learning-using-keras)

- [Pytorch: ResNet](https://pytorch.org/hub/pytorch_vision_resnet/)

- [Analytics Vidhya: how to master transfer learning using pytorch](https://www.analyticsvidhya.com/blog/2019/10/how-to-master-transfer-learning-using-pytorch/?utm_source=blog&utm_medium=transfer-learning-the-art-of-fine-tuning-a-pre-trained-model)

- [Towards Data Science: An overview of ResNet](https://towardsdatascience.com/an-overview-of-resnet-and-its-variants-5281e2f56035) 
