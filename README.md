

# SA-C-GENDER-CLASSIFIER
# Algorithm
1. First install deepface library
2. to install deepface library use the command pip install deepface
3. And also import cv2 and matplotib.pyplot
4. Then read the image,an then show the image

## Program:
```
/*
Program to implement 
Developed by   : ELURU GANESH
RegisterNumber :  212220230016
*/
```

```python
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('th.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:
![go](https://user-images.githubusercontent.com/75235006/173242129-f602ba75-4221-4384-8dd5-93e28532957e.png)


YOUTUBE LINK :
https://youtu.be/QaA1N46GYEQ
