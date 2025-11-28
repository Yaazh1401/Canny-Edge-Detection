
# WORK SHOP-03: CANNY EDGE DETECTION
### Name: YAAZHINI S
### Register no: 212224230308

# AIM:
To perform Canny Edge Detection model through your laptop.

# PROGRAM:
```
import cv2
import matplotlib.pyplot as plt
```
```
img = cv2.imread("C:\\Users\\admin\\Downloads\\yaazh.jpeg")
```
```
blurred =cv2.GaussianBlur(img, (5,5),0)
```
```
edges = cv2.Canny(blurred, 50, 150)
```
```
plt.figure(figsize=(10,5))
plt.subplot(121),plt.imshow(img, cmap='gray')
plt.title('Original Image'), plt.axis('off')
plt.subplot(122),plt.imshow(edges, cmap='gray')
plt.title('Detected Edges'), plt.axis('off')
plt.show()
```
# OUTPUT:

<img width="781" height="425" alt="image" src="https://github.com/user-attachments/assets/c4d32395-d243-4304-9256-9c34362c4234" />


