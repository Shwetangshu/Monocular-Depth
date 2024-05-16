# Monocular Depth

This repository contains code for estimating monocular depth using the MiDaS model in real-time with a webcam.

## Overview

Monocular depth estimation is the task of predicting the depth map from a single 2D image. It has various applications in robotics, autonomous vehicles, augmented reality, and more. In this project, we use the MiDaS (Mixed-scale Dense Attention) model, specifically the small variant, for monocular depth estimation.

The code provided here captures frames from a webcam, processes them through the MiDaS model, and displays the resulting depth map alongside the original frame.

## Setup

To run the code in this repository, you'll need to install the required dependencies:

- Python (>= 3.6)
- OpenCV (`cv2`)
- PyTorch
- Matplotlib

## Usage

1. Clone this repository to your local machine:

   `git clone https://github.com/Shwetangshu/Monocular-Depth.git`

2. Navigate to the cloned repository:

   `cd Monocular-Depth`
   
4. Run the Python script:

   `python midascv.py`


This will launch a window displaying the webcam feed along with the corresponding depth map.

## Credits

- The MiDaS model and its PyTorch implementation are provided by Intel-isl: [https://github.com/intel-isl/MiDaS](https://github.com/intel-isl/MiDaS)
- This project is inspired by the work of researchers and developers in the field of computer vision and deep learning.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
