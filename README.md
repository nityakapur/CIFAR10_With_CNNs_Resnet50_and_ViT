# CIFAR-10 Classification through CNNs, ResNet50 and ViT 

## AIM
This project aims to compare Convolutional Neural Networks (CNNs), Residual Networks (ResNet50), and Visual Transformers (ViT) for object classification using the CIFAR-10 dataset. The goal is to evaluate the accuracy achieved by each model and visualize their performance through loss and accuracy metrics.

## About CIFAR 10
CIFAR-10 is an established computer-vision dataset used for object recognition. It consists of 60,000 32x32 color images containing one of 10 object classes, with 6000 images per class.
The objects included in this specific dataset are : airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.
Kindly refer to the visualization given below: 
```
display_images(training_images, training_labels, training_labels, "Training Data" )
```
<img width="816" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/3bd80243-17c9-4211-affe-c4847869c870">

## Analysis with Convolutional Neural Networks 
The CNNs are the easiest to understand and work with as a beginner in Computer Vision. Despite their simplicity, they offer versatility through features like dropout and various filter optimizations. For this specific project, I have used a regular CNN model without further optimization just to test the strength of the stand-alone model. In terms of accuracy, CNNs had failed to deliver the perfect results and gave a shocking 66% accuracy with CIFAR-10.
Kindly refer to the analytics given below:

<img width="628" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/f777d9e2-90e8-417b-9caa-c40e97203b4e">
<img width="412" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/c90ed543-deb5-4d8c-9d3c-3a39db08ad9a">
<img width="406" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/3c7b5b1c-efce-40ca-a201-21aa4d0080f2">

## Analysis with ResNet50 
ResNet50, characterized by its deep architecture and residual blocks, represents a significant advancement over traditional CNNs. Despite longer training times, ResNet50 achieved an impressive accuracy of 94.5%, outperforming CNNs substantially. 

<img width="805" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/40562c9d-563c-4418-8e33-6b9758b663b5">
<img width="266" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/f87f5ed2-c35b-406b-869d-71326ac8ec6e">
<img width="265" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/67f542f1-a55f-4cb1-bde2-9a7a0e0dfc3c">

## Analysis with Visual Tranformers
Visual Transformers is extremely complex and took the most time to code as well as understand. The model outperformed all the others and achieved an exceptional accuracy of 98%. Tranformers are the most powerful and impactful of all the mentioned models and continually replace LSTMs in NLP and neural networks in CV! The applications and accuracy they offer are indeed the most exciting of them all!

<img width="743" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/f3dec572-390f-4cdf-8279-0c90370ac092">
<img width="578" alt="image" src="https://github.com/nityakapur/CIFAR10_With_CNNs_Resnet50_and_ViT/assets/124587467/ffa68c65-b871-4340-9292-1a06c0f416d4">

## Conclusion
In conclusion, our comparative study reveals that Visual Transformers (ViT) outperform both ResNet50 and traditional CNNs in object classification tasks using the CIFAR-10 dataset. The sequence of accuracy among the models stands as follows:

**Visual Transformers > Residual Networks >> Convolutional Neural Networks**
