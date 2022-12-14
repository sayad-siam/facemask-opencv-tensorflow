# Realtime Facemask Detection System Using OpenCV & TensorFlow
### **"Real-time Face Mask Detection"** is a Deep Learning and Computer Vision project. This project detects human face masks using Python machine learning modules such as OpenCV and TensorFlow. This system is built as a custom deep learning model to detect whether or not a person is wearing a face mask. It will work on both still images and multiple real-time live video footages.
## Motivation
Due to the current **COVID-19** epidemic, there is a strong demand for effective face mask detection applications in order to maintain the safety of transit systems, highly populated areas, residential neighborhoods, major manufacturers, and other businesses. This task is difficult because there aren't many large datasets of 'with mask' photos.
## Framework/Library Used
* *OpenCV*
* *Caffe-based Face Detector*
* *Keras*
* *TensorFlow*
* *MobileNetV2*
## Dataset
The dataset we used consists of 1951 face images collected from Flickr with and without masks. The dataset is created by *Cabani*, *Hammoudi*, *Benhabiles* and *Melkemi* for their [MaskedFace-Net (2020)](https://arxiv.org/abs/2008.08016)
* Without Mask: [Dataset Link](https://drive.google.com/drive/folders/1taHKxS66YKJNhdhiGcEdM6nnE5W9zBb1)
* With Mask: [Dataset Link](https://drive.google.com/drive/folders/1IUzo9KtMYFmWxCsdpPG8QOqhOg93vWxL)
* Face Detection: [HaarCascadeFrontalFace](https://github.com/opencv/opencv/tree/master/data/haarcascades)
## Features
Our face mask detector is accurate and uses no dataset of altered masked photos. Because MobileNetV2 architecture is used, the model may be deployed to embedded systems more easily because it is computationally efficient (Raspberry Pi, Google Coral, etc.). 
Due to the Covid-19 outbreak, this technology can therefore be employed in real-time applications that demand face-mask detection for security reasons. To ensure that public safety regulations are obeyed, this project can be connected with embedded technologies for application at airports, train stations, offices, schools, and public spaces.
## Installation
1. Make sure your device has [Python](https://www.python.org/downloads/) installed.
2. Install [Anaconda](https://www.anaconda.com/). The package will include Jupyter Notebook.
3. Install the following Python packages-
  ```
  pip install tensorflow
  pip install numpy
  pip install matplotlib
  pip install opencv-python
  pip install opencv-contrib-python
  ```
4. Go to the project directory where you downloaded the project. Open command prompt in that directory and type ```jupyter notebook``` in it.
5. Open ```FaceMaskDetect.ipynb```, ```Trust``` it and click ```Kernel``` -> ```Restart and Run All```
6. The system will take upto 8-10 minutes to complete running depending on your device. After completion it will open the Webcam connected to your device (If you have any).
## Screenshots
<img
  src="https://i.ibb.co/rF8Ln5J/NO-MASK-1.jpg"
  alt="Without Facemask"
  title="Without Face Mask"
  style="display: inline-block; margin: 0 auto; width: 400px">
<img
  src="https://i.ibb.co/bFQkpTx/Face-Mask-1.jpg"
  alt="With Facemask"
  title="With Face Mask"
  style="display: inline-block; margin: 0 auto; width: 400px">
## Limitations and Future Plan
* Our system requires good lighting, camera with decent quality and clear frontal view of faces. We have plans to make our system feasible in different lighting conditions.
* The dataset we used has only properly masked faces. We will use dataset of faces of people not wearing mask properly (Nose or Chin area not covered).
* Our system is having hard time detecting faces from shaky inputs (as video or images).
