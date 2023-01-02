# Face Recognition using Keras
This project is a face recognition system implemented using the Keras library and a convolutional neural network (CNN). Given a set of images of known individuals, the system is able to identify the person in new images, The system is trained on a dataset of images of faces and is able to recognize new faces with a high degree of accuracy.

# Execution
The face_recognition.py script expects a directory of images of known individuals as input, and a directory of test images to classify. The script will output the predicted class (i.e., the name of the person) for each test image.

Model Training
The model can be trained on a new dataset by running the train_model.py script. The script expects a directory of training images and a file with the class labels (i.e., the names of the individuals). The script will output a trained model file that can be used with the face_recognition.py script.

Evaluation
The model can be evaluated using the evaluate_model.py script. The script expects a directory of test images and a file with the true class labels. The script will output the model's accuracy on the test set.

Limitations
The face recognition system is designed to work with relatively small datasets and may not scale well to larger datasets. Additionally, the system may not perform well on images with large variations in lighting, pose, or background.
 
