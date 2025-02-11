# Digital Image Processing - Assignment 1

## **Objective**
This assignment focuses on fundamental image processing tasks using OpenCV and Matplotlib in Python. The two main tasks are:

1. Extracting a **100×100** region from the center of an image.
2. Converting the image to **HSV color space** and visualizing the Hue, Saturation, and Value components in grayscale.

---

## **Requirements**
Ensure you have the following installed in your Google Colab or local Python environment:

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- PIL (Pillow)
- Google Colab (if using Google Drive for image storage)

To install missing dependencies, run:

```sh
pip install opencv-python numpy matplotlib pillow
```

## **Usage Instructions**
### **Step 1: Mount Google Drive**
If using Google Colab, mount your Google Drive to access images:

```python
from google.colab import drive
drive.mount('/content/drive')
```

### **Step 2: Define Image Path**
Update the image path based on your Google Drive storage:

```python
image_path = "/content/drive/MyDrive/8th_semester/digital_image_processing/class1/assignment/chocolate cake.jpeg"
```

### **Step 3: Run the Code**
Use the following functions to perform the tasks:

```python
cropped_image = extract_center_region(image_path)
hsv_image = convert_to_hsv(image_path)
```

## **Expected Output**
### **Task 1: Cropped Image**
- Displays a **100×100** cropped region from the center of the image.

### **Task 2: HSV Color Space Conversion**
- Displays three grayscale images representing:
  - **Hue component**
  - **Saturation component**
  - **Value component**
