# CSE471: Deep Learning for Computer Vision

**Session:** 2026-27  
**Credits:** 3  
**L-T-P:** 2-0-2

## Course Outcomes

By the end of the course, students should be able to:

- **CO1:** Remember the fundamental concepts of computer vision, image representation, preprocessing operations, and neural network basics used in deep learning.
- **CO2:** Understand convolutional neural networks, feature extraction, pooling, regularization, and CNN training techniques.
- **CO3:** Apply transfer learning and fine-tuning using pre-trained models for domain-specific computer vision tasks.
- **CO4:** Apply object detection and localization techniques, including bounding box representation, IoU, NMS, and modern detection architectures.
- **CO5:** Apply image segmentation methods and transformer-based vision architectures to extract meaningful visual information from images.
- **CO6:** Understand generative vision models, vision-language models, and interpretability techniques used in advanced computer vision applications.

## Syllabus

### Unit I: Foundations of Computer Vision and Deep Learning
Role of computer vision in modern AI applications; traditional versus deep-learning-based vision approaches; image fundamentals; pixels, channels, and color spaces; resizing, cropping, and normalization; neural network basics; perceptron and feedforward networks; activation functions; loss functions; optimization methods.

### Unit II: Convolutional Neural Networks and Training Techniques
CNN basics: convolutional neural networks, convolution operation, filters, feature maps, padding, stride, pooling, and receptive fields; modern CNN architectures: LeNet, AlexNet, VGG, ResNet, and Inception; regularization techniques; batch normalization and dropout; data augmentation; learning-rate scheduling; weight initialization; early stopping.

### Unit III: Transfer Learning and Fine-Tuning for Vision Tasks
Pre-trained architectures; transfer learning with ResNet, EfficientNet, and MobileNet; feature extraction; fine-tuning; freezing and unfreezing layers; layer-wise learning rates; domain adaptation and datasets.

### Unit IV: Object Detection and Localization
Object detection principles and algorithms; bounding-box representation; intersection over union (IoU); non-maximum suppression (NMS); classical detection pipelines; R-CNN; single-stage detectors; YOLO variants; SSD; RetinaNet with focal loss; evaluation metrics: mean average precision (mAP) and IoU thresholds.

### Unit V: Image Segmentation and Advanced Vision Architectures
Semantic and instance segmentation; U-Net and DeepLab architectures; instance segmentation using Mask R-CNN; vision transformers: self-attention, multi-head attention, and positional encoding; transformer-based models, ViT, and Swin Transformer.

### Unit VI: Generative Vision Models
Generative deep learning; variational autoencoders (VAEs); GAN architectures: DCGAN, CycleGAN, and StyleGAN; image generation; image-to-image translation; super-resolution; vision-language models: CLIP for image-text alignment; interpretability techniques: Grad-CAM and saliency maps.

## Practicals / Experiments

1. Load an image using OpenCV; resize it, convert it to grayscale, normalize it, and visualize the results in Matplotlib subplots.
2. Implement 2D convolution using NumPy; apply different filters to a grayscale image patch and visualize the resulting feature maps.
3. Implement 2D convolution using NumPy; apply different filters to a grayscale image patch and visualize the resulting feature maps. *(This repeats Practical 2 in the supplied syllabus.)*
4. Train LeNet and ResNet-18 on MNIST; compare training time, accuracy, and model size to understand how architectural depth and skip connections influence performance.
5. Use a pre-trained model to extract image features and train a classifier on CIFAR-10 or a small custom dataset, such as flower images. Evaluate the classifier's accuracy.
6. Fine-tune a pre-trained MobileNet on a small Cats vs. Dogs dataset. Experiment with freezing and unfreezing layers and observe the effect on training time and accuracy.
7. Use a pre-trained YOLO model to detect objects in images or webcam/video streams; draw bounding boxes and class labels, and analyze detection confidence and performance.
8. Fine-tune a pre-trained Faster R-CNN model on a small custom dataset; train for a few epochs and evaluate performance.
9. Use a pre-trained U-Net model to generate pixel-wise segmentation masks; overlay the predicted mask on the original image and analyze the model's ability to segment objects.
10. Classify images using a pre-trained CNN, then apply Grad-CAM to visualize which image regions contributed to predictions. Compare correctly classified and misclassified samples.

## Textbook

- Nikhil Singh and Paras Ahuja, *Fundamentals of Deep Learning & Computer Vision*, BPB Publications.

## References

1. Amit Kumar Das, Saptrishi Goswami, Pabitra Mittra, and Amlan Chakrabarti, *Deep Learning*, Pearson Education India.
2. Bharat Sikka, *Elements of Deep Learning for Computer Vision*, BPB Publications.
3. Rajalingappaa Shanmugamani, *Deep Learning for Computer Vision: Expert Techniques to Train Advanced Neural Networks Using TensorFlow and Keras*, Packt Publishing.
