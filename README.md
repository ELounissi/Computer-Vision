# Computer-Vision

This repository is made to contain code and data related to computer vision, I hope they can be useful to researchers.


### 1- Statistical image descriptors

📂 **The folder Shape Statistics**: Contains Python code inside `shape_statistics.ipynb` used for the calculation of many statistical properties of images. The following properties are calculated:

- **Mean**: The average pixel intensity value of the image.
- **Standard Deviation**: The spread of pixel intensity values in the image.
- **Statistical Moments**: Moments that describe the distribution of pixel intensities in the image, which are useful for shape analysis and other higher-order image processing tasks.

  - **m00**: The zeroth moment, representing the total mass of the image.
  - **m10**: The first moment in the x-direction.
  - **m01**: The first moment in the y-direction.
  - **m20**: The second moment in the x-direction.
  - **m11**: The mixed moment (xy), describing the correlation between x and y.
  - **m02**: The second moment in the y-direction.
  - **m30**: The third moment in the x-direction.
  - **m21**: The mixed third moment (x²y).
  - **m12**: The mixed third moment (xy²).
  - **m03**: The third moment in the y-direction.
  - **mu20**: Centralized second moment in the x-direction.
  - **mu11**: Centralized mixed second moment (xy).
  - **mu02**: Centralized second moment in the y-direction.
  - **mu30**: Centralized third moment in the x-direction.
  - **mu21**: Centralized mixed third moment (x²y).
  - **mu12**: Centralized mixed third moment (xy²).
  - **mu03**: Centralized third moment in the y-direction.
  - **nu20**: Normalized second moment in the x-direction.
  - **nu11**: Normalized mixed second moment (xy).
  - **nu02**: Normalized second moment in the y-direction.
  - **nu30**: Normalized third moment in the x-direction.
  - **nu21**: Normalized mixed third moment (x²y).
  - **nu12**: Normalized mixed third moment (xy²).
  - **nu03**: Normalized third moment in the y-direction.

- **Hu Moments**: A set of seven values derived from the image moments, used for image analysis and object recognition. These moments are invariant to image scaling, translation, and rotation.

### 2- 360 One-Degree Rotations of Base E Image

📂 **The folder E**: Contains the 360 rotated versions of a base image containing the letter "E", each rotated by 1 degree. The images are named as `E_R000.png`, `E_R001.png`, `E_R002.png`, ..., `E_R359.png`.


The base image used for these rotations is shown below:

![Base E Image](/E/E_R000.png)

These images can be used for various purposes such as calculating and verifying image descriptors that are supposed to be resistant or invariant to image rotations, or any project requiring a full rotation of a single image.


---

Elyes Lounissi
