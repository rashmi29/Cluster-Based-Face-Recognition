# Cluster-Based-Face-Recognition

* Objective of this project is to provide a program which identifies a correct person related to shown input image.

* Face recognition system recognizes face from the image. This application uses  the  face image of the user. This image is processed and compared with dataset images, find the matching person and recognized person name is displayed. The main phases of the recognition are Image acquisition, preprocessing, segmentation, feature extraction and classification. When these operations are performed on real time video it takes more time. So cluster is used for faster response. OpenCV(Open Source Computer Vision Library) library is used for face recognition. MPI and MPICH library is used for making cluster.

* OpenCV (Open Source Computer Vision Library) is a library of programming functions mainly aimed at real-time computer vision.It is developed by Intel. The library is cross-platform so it is used on many different platforms. It focuses mainly on real-time image processing and computer vision related applications. If the library finds Intel's Integrated Performance Primitives on the system, In this Project Open CV is used for many  image related transformations.

* Cluster will provide higher performance to system. If program run on many processers simultaneously then it provide faster execution using resources of all cluster nodes. MPI provide a good way to execute a program parallely.

* There are many methods for face recognition, But holistic methods encode entire image and represent image as a code point in higher dimensional image space. PCA and FDA are the holistic methods which projects N x N image into some less number of key features. In this project PCA (Principal component analysis) is used for Feature extraction.
