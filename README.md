# Required enviroment:
    Numpy
    Nibabel
    Scipy
    Skimage



# Brain-tumor-detection-based-on-a-novel-and-high-quality-prediction-of-the-tumor-pixel-distributions

[1] Y. Sun, C. Wang, Brain tumor detection based on a novel and high-quality prediction of the tumor pixel distributions, Computers in Biology and Medicine, vol. 172, 2024, 108196. https://doi.org/10.1016/j.compbiomed.2024.108196.

Abstract: The work presented in this paper is in the area of brain tumor detection. We propose a fast detection system with 3D MRI scans of Flair modality. It performs 2 functions, predicting the gray level distribution and location distribution of the pixels in the tumor regions and generating tumor masks with pixel-wise precision. To facilitate 3D data analysis and processing, we introduce a 2D histogram presentation encompassing the gray-level distribution and pixel-location distribution of a 3D object. In the proposed system, specific 2D histograms highlighting tumor-related features are established by exploiting the left-right asymmetry of a brain structure. A modulation function, generated from the input data of each patient case, is applied to the 2D histograms to transform them into coarsely or finely predicted distributions of tumor pixels. The prediction result helps to identify/remove tumor-free slices. The prediction and removal operations are performed to the axial, coronal and sagittal slice series of a brain image, transforming it into a 3D minimum bounding box of its tumor region. The bounding box is utilized to finalize the prediction and generate a 3D tumor mask. The proposed system has been tested extensively with the data of more than 1200 patient cases in BraTS2018∼2021 datasets. The test results demonstrate that the predicted 2D histograms resemble closely the true ones. The system delivers also very good tumor detection results, comparable to those of state-of-the-art CNN systems with mono-modality inputs. They are reproducible and obtained at an extremely low computation cost and without need for training.
