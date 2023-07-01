# Sinogram-Analysis

## CT and Artifacts
Computed Tomography (CT) is a medical imaging technique that provides cross-sectional images of the body. In order to generate highly precise three-dimensional images of anatomical structures for use in medical problems, CT utilizes multiple X-ray projections from different angles. The information CT provides makes it an invaluable asset in the medical world. 

Artifacts, or distortions that may appear in CT image scans, introduce inaccuracies into the anatomical data that is being captured. This may lead to misinterpretation, resulting in diagnostic errors or compromised treatment decisions. Eliminating artificats is crucial in CT imaging to ensure high quality information.

## CT Reconstruction
A CT scan consists of a "collection" of 2D projections. The conversion of these projections into a higher dimensional map of the structure or object is called reconstruction. There are many reconstruction algorithms available for use in obtaining meaningful and interpretable images from raw CT data. 

![DA1DB1C2FF6](https://github.com/spresman/Sinogram-Analysis/assets/66577070/7cbfa310-d2cb-4b76-830e-c93be123c34f)


## Sinogram
A sinogram serves an important role as an intermediate representation of the acquired CT projection data. A sinogram is a representation of the projections on a (t, θ) plane instead of the (x, y) space we are familiar with. THe horizontal axis (θ) represents projection angles, while the vertical axis (t) consists of the position along the detector. Each element of a sinogram captures useful information about specific angles and positions, and provides a comprehensive representation of the primary information. Further analysis and processing can be applied to the sinograms. 

![SinogramProblem24](https://github.com/spresman/Sinogram-Analysis/assets/66577070/a24bf58c-dcca-47c1-9321-1249b34e01ce)


## This Repository
This repository is a quick Python-based analysis of CT data. We generate a sinogram for the CT scan of a human brain, and explore methods to obtain the original image from the computed sinogram. We conclude our analysis with knocking out some X-ray detectors and knocking out some view angles to understand their respective contributions to the CT reconstruction. 
