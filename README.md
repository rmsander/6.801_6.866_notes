# MIT 6.801/6.866: Machine Vision
This repository contains notes and LaTeX for MIT's 6.801/6.866 Machine Vision course from the Fall 2020 semester.  This course is taught by Professor Berthold K.P. Horn, and focuses on geometric computer vision.

To view the PDF lecture notes, simply select the lecture number from this GitHub repository.  To edit the LaTeX code used to generate these PDFs, you can do so by editing the files in `tex`.

## Overview of Course
This course covers the theretical foundations of machine vision, a branch of artificial intelligence designed for teaching robots to "see" and solve problems in object detection and recognition, edge detection, orientation estimation, photogrammetry, and other pertinent problems in robotics.  The course supplements theory with practical patent applications, such as David Lowe's Scale-Invariant Feature Transform (SIFT).

## Syllabus and Lecture Key
The topics for each lecture can be found below:

* [**Lecture 2**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_2.pdf): Image Formation, Perspective Projection, Time Derivative, Motion Field
* [**Lecture 3**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_3.pdf): Time to Contact, Focus of Expansion, Direct Motion Vision Methods, Noise Gain
* [**Lecture 4**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_4.pdf): Fixed Optical Flow, Optical Mouse, Constant Brightness Assumption, Closed Form Solution
* [**Lecture 5**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_5.pdf): TTC and FOR Montivision Demos, Vanishing Point, Use of VPs in Camera Calibration
* [**Lecture 6**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_6.pdf): Photometric Stereo, Noise Gain, Error Amplification, Eigenvalues and Eigenvectors Review
* [**Lecture 7**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_7.pdf): Gradient Space, Reflectance Map, Image Irradiance Equation, Gnomonic Projection
* [**Lecture 8**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_8.pdf): Shape from Shading, Lunar Surface, Scanning Electron Microscope, Green's Theorem in Photometric Stereo
* [**Lecture 9**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_9.pdf): Shape from Shading, General Case - From First Order Nonlinear PDE to Five ODEs
* [**Lecture 10**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_10.pdf): Characteristic Strip Expansion, Shape from Shading, Iterative Solutions
* [**Lecture 11**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_11.pdf): Edge Detection, Subpixel Position, CORDIC, Line Detection, (US 6,408,109)
* [**Lecture 12**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_12.pdf): Blob analysis, Binary Image Processing, Use of Green's Theorem, Derivative and Integral as Convolutions
* [**Lecture 13**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_13.pdf): Object detection, Recognition and Pose Determination, PatQuick (US 7,016,539)
* [**Lecture 14**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_14.pdf): Inspection in PatQuick, Hough Transform, Homography, Position Determination, Multi-Scale
* [**Lecture 15**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_15.pdf): Alignment, recognition in PatMAx, distance field, filtering and sub-sampling (US 7,065,262)
* [**Lecture 16**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_16.pdf): Fast Convolution, Low Pass Filter Approximations, Integral Images, (US 6,457,032)
* [**Lecture 17**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_17.pdf): Photogrammetry, Orientation, Axes of Inertia, Symmetry, Absolute, Relative, Interior, and Exterior Orientation
* [**Lecture 18**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_18.pdf): Rotation and How to Represent it, Unit Quaternions, the Space of Rotations
* [**Lecture 19**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_19.pdf): Absolute Orientation in Closed Form, Outliers and Robustness, RANSAC
* [**Lecture 20**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_20.pdf): Space of Rotations, Regular Tessellations, Critical Surfaces in Motion Vision and Binocular Stereo
* [**Lecture 21**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_21.pdf): Relative Orientation, Binocular Stereo, Structure from Motion, Quadrics, Camera Calibration, Reprojection
* [**Lecture 22**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_22.pdf): Exterior Orientation, Recovering Position and Orientation, Bundle Adjustment, Object Shape
* [**Lecture 23**](https://github.com/rmsander/6.801_6.866_notes/raw/main/lecture_23.pdf): Gaussian Image and Extended Gaussian Image, Solids of Revolution, Direction Histograms, Regular Polyhedra
* [**Quiz Review 1**](https://github.com/rmsander/6.801_6.866_notes/raw/main/quiz_review_1.pdf): Optical Flow, Photometry, Photometric Stereo, Shape from Shading, Computational Molecules, Patents
* [**Quiz Review 2**](https://github.com/rmsander/6.801_6.866_notes/raw/main/quiz_review_2.pdf): Rotations, Quaternions, Photogrammetry, Extended Gaussian Image, Signals, Systems/Patents


## Editing TeX Files
If you're interested in adding your own notes to the existing TeX files, you can do so by editing the `.tex` files in the `tex/` folder.

## Reference
If you find any of the above content useful, please consider citing Professor Horn's textbook:
```
@book{horn1986robot,
  title={Robot vision},
  author={Horn, Berthold and Klaus, Berthold and Horn, Paul},
  year={1986}
}
```
