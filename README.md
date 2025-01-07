# Image-Processing-cont'd---Computer-Vision

This is a continuation of the previous image processing project. The project includes operations like image manipulation, thresholding, bitwise operations, and masking, along with practical demonstrations of brightness, contrast adjustments, and composite image creation.


## Features and Demonstrations

### **1. Brightness and Contrast Adjustment**
- Adjust the brightness of an image using matrix addition and subtraction.
- Modify the contrast using multiplication.
- Visualize results with side-by-side comparisons:
  - **Darker, Brighter, and Original** images.
  - **Low Contrast, High Contrast, and Original** images.

![Brightness Example](results/brightness.png)
![Contrast Example](results/contrast.png)


### **2. Image Thresholding**
- Perform binary thresholding on grayscale images with adjustable threshold values.
- Use adaptive thresholding for more dynamic results.
- Examples include:
  - Thresholding applied to building windows and music sheet images.
  - Comparison between global and adaptive thresholding.

![Thresholding Example](results/threshold.png)
![Adjusted Thresholding Example](results/thresholdAdjusted.png)


### **3. Bitwise Operations**
- Apply bitwise operations (`AND`, `OR`, `XOR`) to images.
- Combine simple shapes (e.g., rectangle and circle) to demonstrate how these operations work.
- Outputs include:
  - **AND** operation: Intersection of shapes.
  - **OR** operation: Union of shapes.
  - **XOR** operation: Exclusive differences between shapes.

![Bitwise Operations Example](results/bitwise1.png)
![Bitwise Operations Example](results/bitwise2.png)


### **4. Image Masking and Compositing**
- Create masks for an image using thresholding.
- Use masks to extract the foreground or background of an image.
- Overlay a Coca-Cola logo onto a checkerboard background with proper scaling and alignment.

![Image Masking Example](results/masking.png)


## Technologies

- Python 
- OpenCV
- NumPy
- Matplotlib
- PIL
