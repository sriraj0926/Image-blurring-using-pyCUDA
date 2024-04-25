# Image-blurring-using-pyCUDA


## Box Blur using CUDA

This repository contains a Python script to perform a box blur operation on an image using CUDA.

### Prerequisites

- Python 3
- OpenCV (`opencv-python` package)
- PyCUDA
- CUDA-enabled GPU

### Installation

1. Ensure you have Python 3 installed.
2. Install required Python packages: pip install opencv-python pycuda
3. Make sure you have a CUDA-enabled GPU and the CUDA Toolkit installed.

### Usage

1. Clone or download this repository.
2. Place your input image(s) in the repository directory.
3. Modify the `image_path` variable in the Python script to point to your input image.
4. Run the Python script: python box_blur_cuda.py
5. The script will display the original and blurred images using OpenCV.

### Customization

- You can adjust the blur radius by changing the value of the `radius` variable in the Python script.
- For different image inputs, modify the `image_path` variable to point to the desired image file.

### Performance

The performance of the box blur operation using CUDA is significantly faster compared to CPU-based implementations, especially for large images and/or large blur radii. The execution time depends on factors such as image size, GPU specifications, and the complexity of the CUDA kernel.

### Notes

- This script assumes grayscale input images. For RGB images, additional modifications to the CUDA kernel and data handling may be required.
- Ensure that the dimensions of the input image(s) are compatible with the block size and grid size specified in the script for optimal performance.
-While executing the code make sure to change the file name.

## Contributions

This code is created by Sriraj Ghali.
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.



