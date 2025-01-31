Image Style Transfer Using Convolutional Neural Networks
This project implements the Neural Algorithm of Artistic Style as described in the paper Image Style Transfer Using Convolutional Neural Networks by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge. The goal of this project is to transfer the artistic style of one image (e.g., a painting) onto the content of another image (e.g., a photograph).

Developed by Shrihari.

Table of Contents
1)Introduction
2)Requirements
3)Examples
4)References
5)License

Introduction
This project uses Convolutional Neural Networks (CNNs) to separate and recombine the content and style of images. The algorithm works by extracting feature representations from a pre-trained CNN (e.g., VGG-19) and optimizing a new image to match the content of a photograph and the style of an artwork.

Key features:
Transfer artistic styles from famous paintings to photographs.
Control the trade-off between content and style.
Generate high-quality stylized images.

Requirements
To run this project, you need the following:
Python 3.7+
PyTorch (or TensorFlow, depending on implementation)
NumPy
Pillow (for image processing)
Matplotlib (for visualization)
OpenCV (optional, for additional image processing)

Examples
Here are some examples of style transfer using this project:

Content Image: A photograph of a city.
Style Image: The Starry Night by Vincent van Gogh.
Output: A stylized cityscape in the style of The Starry Night.

Content Image: A portrait.
Style Image: The Scream by Edvard Munch.
Output: A stylized portrait in the style of The Scream.

Content Image: A landscape.
Style Image: Composition VII by Wassily Kandinsky.
Output: A stylized landscape in the style of Composition VII.

References
Gatys, L. A., Ecker, A. S., & Bethge, M. (2016). Image Style Transfer Using Convolutional Neural Networks. Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR).
VGG-19 Model: Very Deep Convolutional Networks for Large-Scale Image Recognition.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Feel free to contribute to this project by opening issues or submitting pull requests. For any questions, contact Shrihari at shrihari.deshpande0143@gmail.com.


