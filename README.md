# Realistic digital phantoms for prostate ultrasound and photoacoustic imaging

======= MOTIVATION =======

This repository contains 248 sets of realistic digital phantoms for prostate ultrasound and photoacoustic imaging in the male pelvic region. Our model encompasses surrounding tissues or organs around the prostate, including fat, bones (including femoral heads), muscles, urinary bladder, rectum, anal canal, penile bulb, neurovascular bundles, and seminal vesicles. Each digital phantom set contains five parameters: speed of sound, density, acoustic attenuation, optical absorption, and reduced optical scattering. 


======= HOW TO USE =======

The naming format for each digital phantom is as follows

Pelvis_Prostate_TypeOfParameter.mat

Four pelvises in total from the Gold Atlas Project were used including 3_01_P, 3_02_P, 3_03_P, and 3_04_P. 
Sixty-two ex vivo prostate specimens were employed and they are indexed by the date of the data acquisition, e.g., 2021-03-06.
Five parameters were constructed, including optical absorption (abs), acoustic attenuation (att), density (density), optical scattering (scat), and speed of sound (sos).

There is also a mask file indicating the tissue/organ type. Labels of tissue/organ are defined as follows

0 - muscle; 1 - fat; 2 - bone; 3 - prostate; 4 - anal canal; 5 - rectum; 6 - urinary bladder; 7 - neurovascular bundles; 8 - penile bulb; 9 - seminal vescles

The voxel size is 0.875 mm (row) x 0.875 mm (column) x 2.5 mm (depth).


======= CREDITS =======

Please cite 

More information about our studies on prostate ultrasound tomography can be found in
* Wiskin JW, Enders J, Williams C, Turkbey I, Rothberg M, Daneshvar M, Merino M, Xu S, Boctor E, Wu Y, Toubaji A. Imaging of prostate cancer with 3D ultrasound tomography. InMedical Imaging 2022: Ultrasonic Imaging and Tomography 2022 Apr 4 (p. PC1203809). SPIE.
* Williams C, Daneshvar M, Wu Y, Pinto PA, Wiskin J, Klock J, Cwikla M, Malik BH, Love SM, Klock J. MP22-17 PROSTATE ULTRASOUND TOMOGRAPHY (UT): CORRELATION WITH MRI AND WHOLE MOUNT HISTOPATHOLOGY. Ultrasonic Imaging. 2021 Feb.

