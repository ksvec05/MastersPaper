# Masters paper
# Numerical analysis of vehicle telemetry data in rally racing

Telemetry data serve as a vital source of information for analyzing vehicle behavior during rally races, as they provide detailed insight into vehicle movement and dynamics. This master's paper aims to investigate the application of numerical methods to rally vehicle telemetry data and to gain additional information regarding the vehicle's trajectory and dynamic behavior based on available measurements. Data from three rally vehicles, collected during a gravel rally competition, were analyzed, focusing primarily on parameters such as speed, direction of motion, angular velocity, and total acceleration.  

The theoretical and methodological framework of the study encompasses numerical integration, numerical differentiation, interpolation, and numerical filtering. The trapezoidal rule was used to reconstruct 2D vehicle trajectories, while numerical differentiation enabled geometric analysis and the calculation of trajectory curvature. Additionally, vehicle jerk was analyzed. The results demonstrate that numerical methods facilitate a useful analysis of telemetry data, yielding information that cannot be directly determined from the raw measurements. Applying a Savitzky-Golay filter improved the alignment between telemetry derived and geometric curvature. At the same time, limitations related to sampling frequency, noise, and missing values ​​were identified. Ultimately, numerical analysis proves to be a suitable approach for processing telemetry data, provided that the quality and limitations of the input data are duly considered.

Files that are presented are shown in the next table. All files were written in a Jupyter notebook (Python). 

| File  | Description |
| ------------- | ------------- |
| 2d_trajectory_reconstruction.ipynb  | 2D trajectory reconstruction analysis  |
| geometry_analysis.ipynb  | Geometry analysis of 2D trajectory reconstruction and path curvature   |
| jerk_detection.ipynb  | Vehicle jerk detection   |
| vehicle_animation.ipynb  | Vehicle animation along the selected 2D reconstructed path, displaying all calculated elements  |
| ss3_v?_reconstructed.xls  | Vehicle animation auxiliary files containing data from 2D trajectory reconstruction |
| ss3_v?_final.xls | Vehicle animation auxiliary files containing data from jerk detection |
