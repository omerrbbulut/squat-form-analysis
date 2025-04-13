# Squat Form Analysis with MediaPipe

This project analyzes squat form in video using [MediaPipe](https://google.github.io/mediapipe/) and OpenCV.

It performs:
- 2D pose estimation
- Knee angle calculation
- Basic squat depth estimation
- Annotated output video generation

## Demo
![demo](demo.gif)

## Usage

### Run on Google Colab
[Click here to open in Colab](https://colab.research.google.com/)

### Steps
1. Install necessary packages  
2. Upload your `.mp4` video file  
3. Run the squat analysis  
4. Download the output video  

## Dependencies
- Python
- OpenCV
- MediaPipe
- NumPy

### Version Compatibility
This project was tested on Google Colab in April 2025 with the following versions:

- mediapipe-nightly==0.10.21.post20250128
- opencv-python-headless==4.9.0.80
- numpy==1.26.4

These versions ensure compatibility and stability in a notebook-based environment.


## Future Work
- Back posture estimation
- Real-time classification
- CSV logging and graph generation

---

**Author:** Ömer Bulut  
**License:** MIT
