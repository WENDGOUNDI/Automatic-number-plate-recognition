# Automatic-number-plate-recognition

# Dependencies
OpenCV

Matplotlib

Numpy

Imutils

Easyocr

# Process
 - Read the image and convert into grayscale image
  
![image_3](https://user-images.githubusercontent.com/48753146/153378802-f5276b35-8a38-4bb9-958e-546489a65b52.jpg)

 - Apply image processing methods: bilateralFilter, Canny, findContours
  
![apply_filters](https://user-images.githubusercontent.com/48753146/153378944-2f212d47-2e9c-47d1-b50a-d9139db11ed9.png)

 - Apply a mask and extract the plate
  
![apply_mask](https://user-images.githubusercontent.com/48753146/153378934-3c53214e-a00e-49cc-806b-b2b8d49a8d55.png)

 - Apply easyocr library to extract the plate number
  
![results](https://user-images.githubusercontent.com/48753146/153378939-b1b41372-bec8-4b78-b38d-826d92952cb1.png)
