## Background
the HY-1C UVI collects only ***a line image***.  
The UVI imaging procedure is likened to that a camera with a linear CMOS array on the ***focal plane*** collects images in a ***push-broom mode***.  
Five UVI cameras were installed symmetrically around camera 3 on the satellite, camera 3 was taken as the ***reference camera***, and cameras 1, 2, 4, and 5 were taken as the nonreference cameras

## The geometric imaging model
- exterior parameters  
three rotation matrix (angles)
- interior parameters  
a look-angle model is often used to model the normalized detector coordinates

## The geometric calibration between the five UVI cameras
- absolute geometric calibration  
both the ***exterior and interior*** parameters of the reference camera were first calibrated.
- relative geometric calibration  
the exterior parameters of the reference camera were applied to the nonreference cameras  
and only the ***interior parameters*** were then calibrated.

## The normalized detector size difference
After the geometric calibration, we can obtain the normalized coordinates of ***each imaging detector*** in the camera coordinate system of camera 3.

However, the actual normalized detector sizes of the original five UVI cameras differ a lot because ***the largest imaging-detector look angle reaches approximately 56º***.
