
# 🛰️ YOLOv4 Object Detection on Custom Images

## 🎯 Project Overview

This project demonstrates the use of **YOLOv4** (You Only Look Once version 4) implemented using **Darknet** for performing **object detection** on 10 randomly selected images downloaded from the free image website [Pixabay](https://pixabay.com).

The model detects all objects within each image, draws bounding boxes around them, and displays both the **object class names** and their **prediction confidence scores**.

---

## ⚙️ Technologies & Tools Used

- **Programming Language:** Python
- **Execution Environment:** Google Colab
- **Deep Learning Model:** YOLOv4 (Pre-trained on **Darknet**)
- **Libraries:**
  - `opencv-python` (cv2) — for image processing and visualization
  - `numpy` — for numerical computations
  - `matplotlib` — for visualization
  - Google Colab-specific modules:
    - `google.colab.patches` (for displaying images)
    - `google.colab.drive` (for reading/writing from Google Drive)
    - `google.colab.files` (for uploading/downloading files)
  - Standard Python libraries:
    - `os`, `glob`

⚠️ **Note:**  
The `google.colab.*` modules are **built-in to Colab** and do not require installation or inclusion in `requirements.txt`.

---

## 📝 Dataset

- Source: [Pixabay](https://pixabay.com)
- Number of images: 10
- Image format: JPG or PNG
- Images are stored and loaded from **Google Drive**.

---

## 🚀 Project Steps

1. Install required libraries.
2. Set up **Darknet YOLOv4** by downloading pre-trained weights (`yolov4.weights`) and configuration files.
3. Mount Google Drive to access images.
4. Perform object detection on each image using YOLOv4.
5. Display:
   - The original images.
   - The images with detected objects, bounding boxes, class names, and confidence scores.

---

## 🖥️ Code File

- `YOLOv4_code.ipynb`

---

## 🏁 Outputs

✅ Detected objects in each image are highlighted with bounding boxes.  
✅ Class names and confidence levels are visually displayed on the images.


## 🖼️ Example Output Images

Example images showing object detection results:

- ![Detected Objects - Image 1](images/picture1)
- ![Detected Objects - Image 2](images/picture2)


---

## 📦 Requirements

```
opencv-python
numpy
matplotlib

---

## 👩‍💻 Author

**Souzaneh Sehati**  
GitHub: [https://github.com/souzaneh](https://github.com/souzaneh)

---
