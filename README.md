# Moving-Vehicle-registration-plate-detection


# 🚗 Automatic License Plate Recognition (ALPR)

## Overview

The **Automatic License Plate Recognition (ALPR)** project focuses on the detection and recognition of vehicle registration plates from video footage. This technology plays a crucial role in various traffic-related applications, such as toll collection, parking management, and vehicle monitoring systems. The system employs various techniques from computer vision and image processing to accurately extract and recognize license plate information.

## Problem Statement

Automatic recognition and vehicle license plate recognition are key technologies in most traffic-related applications and are actively researched in the field of video processing. Various methods, techniques, and algorithms have been developed for license plate recognition and recognition.

## Aim

To detect and recognize the registration plate of a moving vehicle and convert it into text.

## Algorithm

1. Start
2. Load the video file
3. Convert video to frames
4. Convert frame to grayscale
5. Apply blur on the image
6. Apply filters to find rectangular boxes
7. Apply text recognition on rectangles to find text in the images.
8. Print the registration number.
9. Stop

## Design

- Find all the contours in the image.
- Find the bounding rectangle of every contour.
- Compare and validate the sides' ratio and area of every bounding rectangle with an average license plate.
- Apply image segmentation in the image inside the validated contour to find characters in it.
- Recognize characters using Optical Character Recognition (OCR).

## Conclusion

Thus, a program to detect license registration plates on moving vehicles, using Python code, has been successfully developed and tested.

## References

- "Automatic Number Plate Recognition System (ANPR): A Survey" by Chirag Indravadanbhai Patel.
- Image preprocessing techniques in [OpenCV documentation](https://docs.opencv.org/).

