# Fish Species Classifier

This project demonstrates a convolutional neural network (CNN) built using Python, TensorFlow, and Keras to classify fish species with 95% accuracy. 
The model predicts one of two classes (binary classification): Brook Trout or Smallmouth Bass, based on input images. (Planning to add more classes in the future)

## Features

- **High Accuracy:** Achieved 95% accuracy in distinguishing between Brook Trout and Smallmouth Bass.
- **Binary Classification:** Utilized a binary output layer with a sigmoid activation function to provide probabilities for the two fish classes.
- **Data Augmentation:** Enhanced the robustness of the model by augmenting training data through techniques such as flipping, resizing, and normalization.
- **Grad-CAM Integration:** Implemented Grad-CAM to visualize the areas of an image the model focuses on during classification, making predictions interpretable.

## Technologies Used

- **Python:** For scripting and project implementation.
- **TensorFlow & Keras:** For building, training, and deploying the CNN model.
- **Matplotlib:** For visualizing data and Grad-CAM heatmaps.

## Example Outputs

![image](https://github.com/user-attachments/assets/9f862fb8-3de2-4e9a-ac25-3bd32455f13c)
![image](https://github.com/user-attachments/assets/9e11c1d7-741c-49b0-8202-dcecef307bec)



## Future Improvements
- Add more fish species to expand classification capabilities beyond binary output.
- Optimize model architecture for faster inference without compromising accuracy.
- Explore transfer learning with pre-trained models for enhanced feature extraction.
