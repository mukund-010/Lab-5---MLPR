# Lab-5---MLPR

The aim of this lab was to detect faces in an image and cluster them using K means clustering based on color features. A template image (Shashi Tharoor in this lab) is also classified into one of the clusters.

Faces were detected using OpenCV's Haar Cascade classifier. The detected face regions were converted to HSV color space, then the mean hue and saturation was extracted as features, which were used to perform K means clustering. The Shashi Tharoor image was processed similarly, and its cluster was predicted using the trained K means model.

My key findings was that the faces were successfully grouped into clusters based on the similar color features. Shashi Tharoor was correctly classified into one of the clusters based on hue and saturation. 

My conclusion from this lab is that K means clustering is an effective way of classifying faces based on extracted color features.
The libraries I used were OpenCV, Numpy, Matplotlib and Scikit-learn. All the coding was done in python.

The below image was my first output image. Each face in the picture was detected and highlighted with a square, with the message "A Face" above it.


<img width="1274" height="843" alt="Pasted Graphic" src="https://github.com/user-attachments/assets/10bf17c1-3595-4924-9566-35c5274e47b5" />

The other image output I had is the image of Shashi Tharoor with a box around his face. Again the algorithm was able to detect his face and then highlight it.


<img width="499" height="491" alt="Face detected" src="https://github.com/user-attachments/assets/ec8c185d-b8a6-409c-b80b-cc6e6e3c1261" />


The graphs of the K means clustering is shown in the ipynb file.
