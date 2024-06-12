# Meter Reading Extraction and OCR

This project involves the extraction and recognition of numerical meter readings from images using a combination of image processing techniques and Optical Character Recognition (OCR).

## Image Preprocessing Techniques
1. **Grayscale Conversion**
   - Convert the input image to grayscale to simplify further processing.

2. **Bilateral Filtering**
   - Apply bilateral filtering to reduce noise while preserving edges, enhancing the meter display area.

3. **Edge Detection using Canny Algorithm**
   - Use the Canny edge detection algorithm to identify the edges in the image, which helps in isolating the region of interest.

## Contour Detection and Region Isolation
- **Contour Detection and Approximation**
  - Detect and approximate contours in the preprocessed image to isolate and crop the region containing the meter reading.

## Optical Character Recognition (OCR)
- **EasyOCR Integration**
  - Utilize the EasyOCR library to perform OCR on the cropped image, accurately extracting the numerical values from the meter.

## Visualization
- **Processed Image Display**
  - Display the processed image with the detected meter reading overlaid, providing visual confirmation of the extracted value.

## Versatility and Compatibility
- **Compatibility**
  - Ensure compatibility with various image formats and meter designs, demonstrating the versatility of the solution.

## Example Workflow
1. **Input Image**: Load an image of a meter.
2. **Grayscale Conversion**: Convert the image to grayscale.
3. **Bilateral Filtering**: Apply bilateral filtering to the grayscale image.
4. **Edge Detection**: Use the Canny algorithm to detect edges.
5. **Contour Detection**: Detect and approximate contours to isolate the meter display area.
6. **Crop Region of Interest**: Crop the isolated region containing the meter reading.
7. **OCR Extraction**: Use EasyOCR to extract the numerical values from the cropped image.
8. **Overlay and Display**: Display the processed image with the detected meter reading overlaid.

This approach ensures accurate and efficient extraction of meter readings from images, making it adaptable to various use cases and image conditions.


Dependencies :-
OpenCV (cv2),
Matplotlib (matplotlib),
NumPy (numpy),
Imutils (imutils),
EasyOCR (easyocr),
Make sure to install these dependencies before running the script.
