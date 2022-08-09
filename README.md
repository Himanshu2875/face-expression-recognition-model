# face-expression-recognition-model

The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of five categories (0=Angry, 1=Happy, 2=Neutral, 3=Sad, 4=Surprise). I have used OpenCV's Haar Cascade to do face detection on webcam video frame, video file and draw bounding boxes around them. for this computer vision task, data augmentation is done to increse the dataset by seven fold. In order to train, Convolutional neural network (CNN) with 8 layer is build using softmax layer. Training is done on Google colab as dataset is huge. However, testing can be done on both Jupyter and Google colab for webcam image and video.

## Platform Used - Google Colab and Jupyter
