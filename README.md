# EDGE-DETECTION
## Aim:
To perform edge detection using Sobel, Laplacian, and Canny edge detectors.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:
Import all the necessary modules for the program.

### Step2:
Load a image using imread() from cv2 module.

### Step3:
Convert the image to grayscale

### Step4:
Using Sobel operator from cv2,detect the edges of the image.

### Step5:

Using Laplacian operator from cv2,detect the edges of the image and Using Canny operator from cv2,detect the edges of the image.

## PROGRAM:
DEVELOPED BY: SWETHA S
REGISTER NO: 212222230155

## IMPORT PACKAGES AND LOAD IMAGES:
```
canny=cv2.Canny(gray,120,150)
plt.imshow(canny,cmap='gray')
plt.title("Canny Edge Detector")
plt.axis("off")
plt.show()
```
## SOBEL EDGE DETECTOR:
## SOBEL X:
```
sobelx = cv2.Sobel(gray,cv2.CV_64F,1,0,ksize=5)
plt.imshow(sobelx,cmap='gray')
plt.title("Sobel X axis")
plt.axis("off")
plt.show()
```

## SOBEL Y:
```
sobely = cv2.Sobel(gray,cv2.CV_64F,0,1,ksize=5)
plt.imshow(sobely,cmap='gray')
plt.title("Sobel Y axis")
plt.axis("off")
plt.show()
```

## SOBEL XY:
```
sobelxy = cv2.Sobel(gray,cv2.CV_64F,1,1,ksize=5)
plt.imshow(sobelxy,cmap='gray')
plt.title("Sobel XY axis")
plt.axis("off")
plt.show()
```

## LAPLACIAN EDGE DETECTOR:
```
lap=cv2.Laplacian(gray,cv2.CV_64F)
plt.imshow(lap,cmap='gray')
plt.title("Laplacian Edge Detector")
plt.axis("off")
plt.show()
```

## CANNY EDGE DETECTOR:
```
canny=cv2.Canny(gray,120,150)
plt.imshow(canny,cmap='gray')
plt.title("Canny Edge Detector")
plt.axis("off")
plt.show()
```

## Output:
## ORIGINAL IMAGE:
![image](https://github.com/swethaselvarajm/EDGE-DETECTION/assets/119525603/14512811-4c87-42e7-bb15-599b41627a24)


### SOBEL EDGE DETECTOR
![image](https://github.com/swethaselvarajm/EDGE-DETECTION/assets/119525603/9cc0c9ae-504f-483d-9420-903531f32b2b)

![image](https://github.com/swethaselvarajm/EDGE-DETECTION/assets/119525603/fe690f65-a68a-4c1d-89e5-d344758d8309)

![image](https://github.com/swethaselvarajm/EDGE-DETECTION/assets/119525603/9aa432e3-641c-467f-9605-64743b173b52)


### LAPLACIAN EDGE DETECTOR
![image](https://github.com/swethaselvarajm/EDGE-DETECTION/assets/119525603/845a2bf7-0ca2-4240-bca0-68b5b951fc93)



### CANNY EDGE DETECTOR
![image](https://github.com/swethaselvarajm/EDGE-DETECTION/assets/119525603/453c1073-c198-4116-a0f4-b2f5e3224fd4)


## Result:
Thus the edges are detected using Sobel, Laplacian, and Canny edge detectors.
