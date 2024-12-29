# Master_Thesis_UR3e
**Topic: Vision Guided 6-Axis Robotic Arm For Object Detection on a Conveyor Line** <br>

Universidad de Oviedo <br>
International Postgraduate Center <br>
Master in Mechatronics Engineering (EU4M) <br>
Defended on July 2024 <br>

This work presents an small industrial setup replica for inspection and rejection of objects on a conveyor line. It explains the stepwise calibration of an Intel RealSense L515 RGBD camera and Hand
to Eye Calibration of a UR3E robot and accuracy validation based on practical tests. 

It includes the design and integration of a conveyor system with the robot and cameragripper assembly to perform pick and place operation based on Image (2D) to World (3D) coordinate transformations and various image processing techniques. Three different conveyor inspection scenarios are replicated to detect the objects on the basis of size, color and deficient bolts and integrated on a single program with online visualization of results.

Hereby, I share my final report, presentation and complete code i this repopsitory for your reference to build up on project concept and carry out improvements and in case of any questions feel free to contact me.

# Objectives

Primary:
1. Develop and Integrate a Vision-guided robotic system for the purpose of Inspection and Classification.
2. Design and Integration of a Robotic Cell: Conveyor system with UR3E Robot.
3. Develop Object-Detection algorithm for classification and pick-place action.

Secondary:
1. Optimize Camera and Hand-eye calibration for accurate operation.
2. Improvement of Detection and Inspection algorithm in a dynamic scenario.

# Kurzübersicht
To save your time, I provide a small glimpse of topics covered in the project for your aid:
1. Overview of different Coordinate System in use and its Transformation (Translation and Rotation)
2. Camera Intrinsics Concept and its Calibration (Code inc.)
3. Camera Extrinsics Concept and Hand-eye-calibration (Code inc.)
4. System Design (Software and Hardware Integration)
<p align="center">
  <img src="Miscellaneous/Software_Setup.png" width="50%" height="250">
</p>  
<p align="center">
  <img src="Miscellaneous/Hardware_Integration.png" width="50%" height="250">
</p>
6. Conversion of 2D pixel co-ordinates to 3D World coordinates
7. Image Processing Algorithm detailed explanation to reject defective objects on conveyor (Based on size, color and deficient bolts)
8. Video 1: For Camera calibration accuracy check and Coordinate conversion (2D to 3D)
9. Video 2: Final outcome showing the three different detection scenarios

Thank you and have a good day. 
  











