# Lens Distortion Calibration & Correction with OpenCV
Personal Mini Project, Distortion Calibration &amp; Correction with OpenCV
This project demonstrates how to estimate and correct camera lens distortion using OpenCV’s calibration tools.

## 🔍 Overview

In optical and metrology systems, precise calibration is essential to ensure the accuracy of measurements. This simulation uses a set of chessboard-pattern images to estimate camera intrinsic parameters and distortion coefficients, then applies correction to distorted images.

## 📦 Features

- Detect chessboard corners using `cv2.findChessboardCorners`
- Estimate camera matrix and distortion coefficients with `cv2.calibrateCamera`
- Undistort new images using calibration results
- Visualize and compare distortion before and after correction

## 🛠️ Technologies

- Python 3
- OpenCV
- NumPy / Matplotlib

## 📁 Structure
lens_calibration_project/
├── calibration_images/ # Chessboard input images
├── src/
│ ├── calibrate_camera.py # Run calibration
│ ├── undistort_test.py # Apply correction to new images
├── results/ # Output images
├── README.md
└── requirements.txt

## 📚 References

- [OpenCV Camera Calibration Docs](https://docs.opencv.org/4.x/dc/dbb/tutorial_py_calibration.html)
- [Kaggle: Calibration Images](https://www.kaggle.com/datasets/vpavlenko/camera-calibration-images)

## 🧑‍💻 Author

Xiuyu Tang – [LinkedIn](https://www.linkedin.com/in/your-link/)  
MIT License
