# Fundamental Computer Vision

Programming assignments for **EEE3545: Fundamental Computer Vision** at Yonsei University (Fall 2026).

## HW1: Panorama to Perspective Projection

**Topic:** Converting a 360° Equirectangular Projection (ERP) panorama into perspective images using Plücker rays.

- Implemented coordinate transformations between ERP panorama and perspective views.
- Applied camera orientation (yaw and pitch) to generate images from different viewing directions.
- Implemented bilinear interpolation for image sampling.
- Explored the effects of field of view (FOV) on perspective projection.

**Files:** `HW1/HW1.ipynb`

## HW2: Virtual Camera Projection and Homography

**Topic:** Simulating the projection of a planar image through a virtual camera.

- Implemented 3D-to-2D perspective projection using camera intrinsic and extrinsic parameters.
- Constructed a planar homography matrix to map poster coordinates to image coordinates.
- Applied perspective warping and inverse homography for image transformation and rectification.
- Analyzed the effects of focal length and camera depth on projected image size.
- Explored the limitations of homography in 3D scenes with parallax.

**Files:** `HW2/HW2.ipynb`

## Tools

Python · NumPy · Matplotlib · OpenCV · Pillow · scikit-image · Jupyter Notebook