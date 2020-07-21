# Semantic segmentation of plant organs using Encoder/Decoder network and RGB-D images



This project is about semantic segmentation of 4 classes of plant organs (stem, petiole, leaf and fruit) from RGB-D images using Pyhton 3, Tensorflow 2.0 and Keras. I worked with synthetic data, randomly generated and annotated with Blender and used an Encoder/Decoder architecture trained from Scratch with 10000 images.








<img width="931" alt="Capture d’écran 2020-07-19 à 11 33 46" src="https://user-images.githubusercontent.com/62508367/87871785-c46c9200-c9b3-11ea-8ae5-21af796d4697.png">


# 1.Training & Evaluation

The model was trained on 10000 images ( 8000 images for training, 1000 images for validation and 1000 for test ) of size 224x224 on 4x12Go GPU, the curves of accuracy and loss were good as shown below:

<img width="1023" alt="Capture d’écran 2020-07-20 à 23 05 22" src="https://user-images.githubusercontent.com/62508367/87986532-87042380-cadd-11ea-9d1e-9a0828ace184.png">



# 2.Inference

The model was tested on 1000 RGBD images, here is some results: // //
  
<img width="595" alt="Capture d’écran 2020-07-21 à 15 53 14" src="https://user-images.githubusercontent.com/62508367/88063437-51f1e280-cb6a-11ea-9f4b-a56c2f67494f.png">

