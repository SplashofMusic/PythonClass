# PythonClass
This is a collection of notes and scripts from a Python class that was from September to December 2107.
As a part of the class, I worked on a fun project that determines the breed of a cat.
### What This Project Is About:
This project is a cat breed classifier. It uses an input of a cat image to try and predit its breed.
### How It Works:
This project uses a basis of neural network technology. In order for the neural network to function, it needs to be trained by feeding it data (i.e cat images of different breeds). The process of finding cat images on the web takes a long time, so we narrowed it down to three distinct cat breeds, Maincoon, Ragdoll, and the Japanese Bobtail.
To train the classifier, we used a well known arcitecture called VGG16. The Python frameworks we utilized were tensorflow and karas. The karas framework makes it easy to take an existing VGG16 model and retrain it to classify different images.
### Output:
After the network is trained, we saved the work to a karas model file so we could run it later. The output is a probability of which breed it looks like the most. The classifier takes the breed with the highest probability and that would be the result.
### Future Improvements:
The current classifier is severly overfitting. In the future, we need to connect a whole lot more training images.
