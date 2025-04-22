This project demonstrates Neural Style Transfer (NST) using a pre-trained VGG19 model in PyTorch. NST is a deep learning technique that blends the content of one image with the style of another, producing a unique artistic result.

Key Components:
Content Image: A real-world image that provides the structural elements.

Style Image: An artwork or painting that contributes stylistic textures.

VGG19 Model: A pre-trained convolutional neural network used to extract content and style features.

Loss Functions:

Content Loss: Measures similarity to the original image.

Style Loss: Measures similarity to the painting's textures using Gram matrices.

Optimization: The content image is iteratively updated to minimize the combined content and style loss.

 Output:
A stylized image that retains the structure of the content image while adopting the artistic style of the chosen painting.
