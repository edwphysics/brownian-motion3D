# brownian-motion3D
This module analyses the motion of a Brownian particle in three dimensions. It is divided into calibration and mean square displacement (MSD). The calibration is performed using NonlinearModelFit[] and LinearModelFit[] in two different .nb modules: calibrationV8.nb (linear) and calibrationV8-nonlinear.nb, each evaluating R in pixels (px) or micrometers (um). Finally, the module MSDV2.nb analyses the data of the MSD for the particles measured.

To compile the modules you must change the dataPaths depending on the folders that contain the data. Also, examine the data and ensure that the structure is compatible with the Import[] function. Then, run the entire notebook with Evaluation -> Evaluate Notebook.
