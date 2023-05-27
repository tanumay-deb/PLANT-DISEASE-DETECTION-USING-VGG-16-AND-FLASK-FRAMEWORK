# Plant Disease Detection using VGG16 and Flask Framework

This project aims to detect plant diseases using the VGG16 convolutional neural network (CNN) architecture and the Flask web framework. The dataset used for training the model is the Plant Village dataset, and only 4000 images were utilized in this project.

## Methodology

The VGG-16 architecture is a widely used CNN architecture known for its effectiveness in image classification tasks. It has gained popularity, especially in the field of deep learning, due to its exceptional performance with the ImageNet dataset. The VGG-16 model was initially developed by Karen Simonyan and Andrew Zisserman in 2014 during their work at Oxford University, titled "Very Deep Convolutional Networks for Large-Scale Image Recognition."

The "V" in VGG-16 represents "Visual," the "G" stands for "Geometry," and the second "G" denotes the research group that contributed to the development of this Convolutional Neural Network model. The number 16 indicates the total number of layers in this neural network architecture.

VGG-16 has achieved outstanding results in the ImageNet dataset, with an accuracy of 88.67%. It was proposed as an improvement over the AlexNet architecture and submitted to the ImageNet Large Scale Visual Recognition Challenge (ILSVRC). In this model, the large kernel-sized filters of numbers 11 and 5 in the first and second convolutional layers, respectively, were replaced by multiple consecutive 3x3 kernel-sized filters.

## Usage

To use this project, follow the instructions below:

1. Clone the repository:

```
git clone https://github.com/your-username/plant-disease-detection.git
```

2. Install the required dependencies. Ensure you have Python and pip installed. Run the following command:

```
pip install -r requirements.txt
```

3. Download the Plant Village dataset and place it in the appropriate directory.

4. Train the VGG16 model using the provided dataset. Adjust the number of images used for training in the configuration file if desired.

5. Once the model is trained, run the Flask web application:

```
python app.py
```

6. Access the web application by navigating to http://localhost:5000 in your web browser.

7. Upload an image of a plant leaf and submit it for disease detection.

## Additional Resources

For more information on the VGG16 architecture and its development, refer to the following resources:

- [Very Deep Convolutional Networks for Large-Scale Image Recognition](https://arxiv.org/abs/1409.1556) by Karen Simonyan and Andrew Zisserman.
- [VGG16 Model for Keras](https://www.cs.toronto.edu/~frossard/post/vgg16/) by Davi Frossard.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to your needs.
