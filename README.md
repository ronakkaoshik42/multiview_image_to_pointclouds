# Multiview images to point clouds

The dataset can be found here https://drive.google.com/drive/folders/1ngdIlWdYWMYGd5xcG6uHYDFXlSoQrqpt?usp=sharing
(Too large for github)

## Structure from Motion (SFM) Pipeline with OpenCV

This project is an implementation of a Structure from Motion (SFM) pipeline using Python and OpenCV. SFM is a computer vision technique that reconstructs a 3D scene from a set of 2D images. The pipeline includes key stages such as feature detection, matching, camera calibration, essential matrix estimation, triangulation, bundle adjustment, and point cloud visualization.

## Features:

Implements SFM pipeline using OpenCV's built-in functions.
Processes a sequence of images to reconstruct a 3D scene.
Supports downsampling of images for faster processing.
Provides options for bundle adjustment to refine camera poses and 3D points.
Generates a 3D point cloud from the reconstructed scene.
Outputs point cloud in PLY format for easy visualization.
Usage:

## Clone the repository.
Install the required packages (OpenCV, numpy).
Place your unzipped dataset (images and calibration file) in the specified directory.
Configure and run the notebook.
View the generated point cloud in a PLY viewer.
