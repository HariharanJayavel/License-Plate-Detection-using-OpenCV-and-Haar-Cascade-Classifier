# License Plate Detection using OpenCV’s Haar Cascade Classifier

## Aim
To implement a **license plate detection system** using **OpenCV** and a **Haar Cascade Classifier** (`haarcascade_russian_plate_number.xml`) to automatically locate vehicle license plates in images.

---

## Software Requirements
- **Python 3.x**
- **OpenCV (cv2)**
- **NumPy**
- Sample vehicle images
- `haarcascade_russian_plate_number.xml`

---

## Algorithm Steps

1. **Read the input image** and convert it to **grayscale** for easier processing.  
2. **Load the Haar Cascade Classifier** for license plate detection (`haarcascade_russian_plate_number.xml`).  
3. **Apply `detectMultiScale()`** to locate potential license plate regions in the image.  
4. **Draw rectangles** around the detected license plate regions to highlight them.  
5. **Display or save the output image** showing detected license plates. 

## Result
The system successfully detects and marks the license plate region(s) in the given vehicle image using a green rectangle.