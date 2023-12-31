# EE243_Advanced_computer_vision
Main Project and multiple mini-projects involved in the course Advanced Computer Vision

My DeepLabv3 implementation and Experiments - 

  Semantic segmentation plays a crucial role in computer vision tasks by assigning a class label to each pixel in an image. In this project, I explore the DeepLabv3 architecture for semantic segmentation, which combines powerful features of convolutional neural networks with the advantages of the atrous spatial pyramid pooling (ASPP) module. My goal is to accurately segment objects in images and improve the understanding of their spatial context.
  To achieve this, I implement the DeepLabv3 model us- ing PyTorch, leveraging the ResNet-50 backbone and ASPP module. The encoder network extracts high-level features, capturing contextual information, while the decoder network recovers spatial details for precise segmentation. I train the model on a dataset of labeled images using the Adam optimizer and cross-entropy loss function and evaluate its performance on a validation set.
  Throughout the training process, I monitor the loss and track the validation loss to ensure model convergence. Additionally, I calculate the mean Intersection over Union (mIoU) metric to assess the segmentation accuracy. The trained model demonstrates impressive results in semantic segmentation tasks, accurately delineating objects and pre-serving spatial context.
  My experiments showcase the effectiveness of the DeepLabv3 architecture and its compatibility with the Adam optimizer for achieving accurate and detailed segmentation results. The mIoU metric serves as an effective measure of performance, providing insights into the model’s ability to capture object boundaries and handle class imbalances. The trained model can be utilized in various computer vision applications, including scene understanding, autonomous driving, and medical image analysis.


  The mini projects involve relationships between the 3D world and 2D images, visual tracking, visual recognition of objects and events, higher-level reasoning for scene understanding, projective geometry, modeling and calibrating cameras, geometric primitives and their uncertainty, stereo vision, motion analysis, and approximating three-dimensional data.
