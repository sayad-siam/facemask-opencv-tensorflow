# Realtime Facemask Detection System Using OpenCV & TensorFlow
### **"Real-time Face Mask Detection"** is a Deep Learning and Computer Vision project. This project detects human face masks using Python machine-learning modules such as OpenCV and TensorFlow. This system is built as a custom deep-learning model to detect whether or not a person is wearing a face mask. It will work on both still images and multiple real-time live video footage.
## Motivation
Due to the current **COVID-19** epidemic, there is a strong demand for effective face mask detection applications in order to maintain the safety of transit systems, highly populated areas, residential neighborhoods, major manufacturers, and other businesses. This task is difficult because there aren't many large datasets of 'with mask' photos.
## Framework/Library Used
* *OpenCV*
* *Caffe-based Face Detector*
* *Keras*
* *TensorFlow*
* *MobileNetV2*
## Dataset
The dataset consists of 1951 face images collected from Flickr with and without masks. The dataset is created by *Cabani*, *Hammoudi*, *Benhabiles* and *Melkemi* for their [MaskedFace-Net (2020)](https://arxiv.org/abs/2008.08016)
* Without Mask: [Dataset Link](https://drive.google.com/drive/folders/1taHKxS66YKJNhdhiGcEdM6nnE5W9zBb1)
* With Mask: [Dataset Link](https://drive.google.com/drive/folders/1IUzo9KtMYFmWxCsdpPG8QOqhOg93vWxL)
* Face Detection: [HaarCascadeFrontalFace](https://github.com/opencv/opencv/tree/master/data/haarcascades)
## Features
Our face mask detector is accurate and uses no dataset of altered masked photos. Because MobileNetV2 architecture is used, the model may be deployed to embedded systems more quickly because it is computationally efficient (Raspberry Pi, Google Coral, etc.). 
Due to the Covid-19 outbreak, this technology can be employed in real-time applications that demand face-mask detection for security reasons. To ensure that public safety regulations are obeyed, this project can be connected with embedded technologies for application at airports, train stations, offices, schools, and public spaces.
## Installation
1. Ensure your device has [Python](https://www.python.org/downloads/) installed.
2. Install [Anaconda](https://www.anaconda.com/). The package will include Jupyter Notebook.
3. Install the following Python packages-
  ```
  pip install tensorflow
  pip install numpy
  pip install matplotlib
  pip install opencv-python
  pip install opencv-contrib-python
  ```
4. Go to the project directory where you downloaded the project. Open the command prompt in that directory and type ```jupyter notebook``` in it.
5. Open ```FaceMaskDetect.ipynb```, ```Trust``` it and click ```Kernel``` -> ```Restart and Run All```
6. The system will take up to 8-10 minutes to complete running depending on your device. After completion, it will open the Webcam connected to your device (If you have any).
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
## Limitations and Future Plans
* Our system requires good lighting, a camera with decent quality and a clear frontal view of faces. We have plans to make our system feasible in different lighting conditions.
* The dataset we used has only properly masked faces. We will use a dataset of faces of people not wearing masks properly (The nose or Chin areas are not covered).
* Our system is having a hard time detecting faces from shaky inputs (such as video or images).
## References
1. [Cabani, Adnane, Karim Hammoudi, Halim Benhabiles, and Mahmoud Melkemi. "MaskedFace-Net–A dataset of correctly/incorrectly masked face images in the context of COVID-19." *Smart Health* 19 (2021): 100144.](https://www.sciencedirect.com/science/article/pii/S2352648320300362)
2. [Ge, Shiming, Jia Li, Qiting Ye, and Zhao Luo. "Detecting masked faces in the wild with lle-cnns." In *Proceedings of the IEEE conference on computer vision and pattern recognition*, pp. 2682-2690. 2017.](https://openaccess.thecvf.com/content_cvpr_2017/html/Ge_Detecting_Masked_Faces_CVPR_2017_paper.html)
3. [Hammoudi, Karim, Adnane Cabani, Halim Benhabiles, and Mahmoud Melkemi. "Validating the CorrectWearing of Protection Mask by Taking a Selfie: Design of a Mobile Application “CheckYourMask” to Limit the Spread of COVID-19." *Computer Modeling in Engineering and Sciences* 124, no. 3 (2020): 1049-1059.](https://hal.science/hal-03323304/)
4. [Karras, T., Laine, S., & Aila, T. (2019). A style-based generator architecture for generative adversarial networks. In *Proceedings of the IEEE/CVF conference on computer vision and pattern recognition* (pp. 4401-4410).](https://openaccess.thecvf.com/content_CVPR_2019/html/Karras_A_Style-Based_Generator_Architecture_for_Generative_Adversarial_Networks_CVPR_2019_paper.html)
5. [Action Sant´e-Social Cote ˆ d’Ivoire. (2020). *Comment bien mettre son masque*.](https://www.facebook.com/110412877115436/photos/comment-bien-mettreson-masque/154573562699367/)
6. [Africa Centres for Disease Control and Prevention - Africa CDC, African Union. (2020). *How to wear a face mask correctly*.](https://africacdc.org/download/how-to-wear-a-face-mask-correctly/)
7. [Bouteiller, J. (2020). Coronavirus. *Comment bien porter son masque ? Les conseils d’une infirmi`ere de la m´etropole de Lille*.](https://actu.fr/hauts-de-france/lille_59350/coronavirus-comment-bien-porter-masque-conseils-dune-infirmiere_32651335.html)
8. [Colart, L. (2020). *Le port du masque: Les gestes `a faire et ne pas faire*.](https://www.lesoir.be/sites/default/files/dpistyles_v2/ena_16_9_in_line/2020/04/21/node_296003/27512244/public/2020/04/21/B9723268640Z.1_20200421182927_000GBLFTKA92.1-0.jpg?itokvge-65yl1587734455)
9. [Daclin, C. (2020). *Coronavirus : Où et `a quel ˆage les enfants doivent-ils porter le masque*?](https://www.rtl.fr/actu/bien-etre/coronavirus-ou-et-a-quel-age-les-enfants-doivent-ils-porter-le-masque-7800688133)
10. [Mask Dataset](https://makeml.app/datasets/mask)
