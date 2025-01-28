# Smoke Soot Analysis and Height Estimation Using Computer Vision

This repository contains an image processing workflow for analyzing smoke soot using computer vision techniques. The program is implemented in Python and executed in a Google Colab environment for easy setup and usage.

## Example Results  
![Screenshot from 2025-01-27 18-59-16](https://github.com/user-attachments/assets/637e7d6e-8467-43db-b1f1-97d59be3b5c5)

<p align="center">
  <img src="https://github.com/user-attachments/assets/9fb15663-96b8-4ae7-8659-ca54395315c2" alt="Result 1" width="45%">
  <img src="https://github.com/user-attachments/assets/c5e8f659-67c9-42bd-b310-5af93f9a025a" alt="Result 2" width="45%">
</p>


## Features
- Mount and manage assets directly from Google Drive
- Convert input images to grayscale for preprocessing
- Detect extreme points of smoke soot and calculate the height magnitude
- Apply various image processing techniques:
  - Cropping the area of interest (AOI)
  - Gaussian blur and thresholding
  - Morphological transformations
  - Contour detection and edge visualization
- Generate and visualize the final output with annotated height measurements

## Dependencies
The following libraries are required to run the program:
- OpenCV
- NumPy  
- Matplotlib
- Google Colab (optional, for cloud execution)

## How to Use
1. Clone the repository:
```bash
git clone (https://github.com/kashifansaricodes/Smoke-Soot-Analysis-and-Height-Estimation-Using-Computer-Vision.git)
cd <repository-folder>
```

2. Open the notebook in Google Colab or any Jupyter environment
3. Mount your Google Drive and define the path to your image assets
4. Run the cells in sequence to:
   - Preprocess the images
   - Analyze smoke soot
   - Visualize the results

## Workflow
1. **Asset Management:** Mount the drive and define the asset path for images
2. **Image Preprocessing:**
   - Read the original image
   - Convert it to grayscale
3. **Smoke Soot Detection:**
   - Manually set threshold points for smoke soot
   - Find extreme y-coordinates for height estimation
4. **Image Processing:**
   - Crop AOI
   - Apply Gaussian blur, thresholding, and morphology
   - Detect and visualize contours
5. **Output Visualization:** Plot the final processed image with height magnitude

## Future Enhancements
- Automate threshold point selection
- Improve processing efficiency with GPU acceleration
- Expand the workflow to detect multiple smoke soot regions simultaneously

## Acknowledgments
Special thanks to the open-source community for the tools and libraries used in this project.
