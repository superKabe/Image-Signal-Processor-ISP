### Image Signal Processor (ISP) Project Overview

In this project, a basic Image Signal Processor (ISP) is developed that converts raw sensor images into vibrant color images. The task involves processing raw binary files containing sensor data and applying a series of image processing techniques to achieve the final output.

Steps:
- **Reading the image**: Start by interpreting the raw binary data to extract the sensor information.
- **Demosaicing**: Convert the raw sensor data into RGB format, enabling the creation of a full-color image.
- **Color Correction**: Using a matrix, adjust the colors to ensure accuracy and natural appearance.
- **Denoising**: Apply a bilateral filter to reduce noise while preserving important details in the image.
- **Edge Enhancement**: Utilize an unsharp mask to enhance the edges, making the image crisper and more defined.
- **Contrast Enhancement**: Finally, use CLAHE (Contrast Limited Adaptive Histogram Equalization) to improve the contrast, bringing out details in both the shadows and highlights.

The final result was a color-corrected, noise-reduced, sharp, and well-contrasted image, saved to an output file for further use.
