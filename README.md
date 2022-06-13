# SA-C-GENDER-CLASSIFIER
# Algorithm:
1. To classify the gender of a person use the DeepFace library.
2. DeepFace library is developed based on deep learning algorithms.
3. Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements.
4. Load and display the imported image.
5. Pass the image to DeepFace library and analyze the image to predict gender of a person.
6. This prediction is stored in result variable.
7. Finally print the prediction using this algorithm.

## Program:
```
/*
Program to implement 
Developed by   : Aditya JV
RegisterNumber : 212220230002
*/
```
```Python
#install deepface
pip install deepface

#import packages
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt

#read the image
img=cv2.imread('GowriM.jpeg')
plt.imshow(img[:,:,::-1])
plt.show()

#Analyze gender
result=DeepFace.analyze(img,actions=['gender'])

#print the gender
print("Gender : ",result['gender'])
```
## OUTPUT:

1. CODE :

![SA - Gender Classifier - Jupyter Notebook and 4 more pages - Profile 1 - Microsoft​ Edge 13-06-2022 14_20_45 (2)](https://user-images.githubusercontent.com/75235386/173318058-de42aabf-150c-4d2e-a62d-f45d4d4c3ea1.png)

2. DEMO VIDEO YOUTUBE LINK: https://youtu.be/0iiM3Tlu584


