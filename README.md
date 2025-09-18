# Facial-Expression-Recognition-with-PyTorch
Facial Expression Recognition with PyTorch uses a pretrained ResNet18 on grayscale face images to classify seven emotions. The first conv layer is adapted for 1-channel input, and the FC layer replaced with a custom head. The model is trained with cross-entropy loss, evaluated with accuracy, and predictions visualized with probability bars.
