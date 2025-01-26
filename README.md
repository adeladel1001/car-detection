# Car Detection Using OpenCV Filters

This project aims to detect cars in images and videos without using pre-trained models. Instead, it utilizes image processing techniques and filters available in the OpenCV library to achieve vehicle detection.

# Features

- **Car detection using OpenCV filters.**
- **No need for pre-trained deep learning models.**
- **Lightweight and efficient processing.**
- **Works on both images and videos.**

# Technologies Used

- **Python**
- **OpenCV**
- **NumPy**

# Usage

1. **Run the script for image detection:**
   ```bash
   python vehicule detection and couting.pyinb --input path/to/image.jpg
   ```

2. **Run the script for video detection:**
   ```bash
   python vehicule detection and couting.pyinb --input path/to/video.mp4
   ```

3. **Adjust the filter parameters in the script to improve detection accuracy.**

# Methodology

The car detection is performed using the following steps:

1. **Preprocessing:**
   - Convert image to grayscale.
   - Apply Gaussian blur to reduce noise.
   - Use edge detection techniques such as Canny edge detector.

2. **Filtering:**
   - Apply morphological operations to enhance vehicle contours.
   - Use contour detection to locate potential vehicles.

3. **Bounding Boxes:**
   - Draw bounding boxes around detected vehicles.
   - Filter out false positives based on area and shape.



# Potential Improvements

- **Enhance detection by tuning filter parameters.**
- **Implement background subtraction for better motion detection.**
- **Add tracking capabilities to follow detected vehicles.**

# Contribution

Feel free to contribute by submitting pull requests or reporting issues.


