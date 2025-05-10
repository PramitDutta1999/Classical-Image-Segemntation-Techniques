# Classical Image Segemntation Techniques

This repository contains a group assignment submitted for **ENGG*6302: Image Processing** at the University of Guelph. The project focuses on classical segmentation techniques in image processing.

## Key Components

- **Region Growing Segmentation**
  - Implements intensity-based region expansion from seed points
  - Tests different thresholds and seed locations
  - Evaluates sensitivity to initial seed selection

- **Mean Shift Segmentation**
  - Applies both custom implementation and `sklearn.cluster.MeanShift`
  - Demonstrates convergence behavior and trajectory visualization
  - Estimates modes and histograms before and after segmentation

## Repository Contents

- `W25_ENGG6302_Assign2_01_region_growing_codes.ipynb`: Region growing segmentation implementation and tests
- `W25_ENGG6302_Assign2_01_mean_shift_v1_codes.ipynb`: First version of custom mean shift with step-by-step convergence
- `W25_ENGG6302_Assign2_01_mean_shift_v2_codes.ipynb`: Enhanced version using `scikit-learn`’s built-in MeanShift clustering

## Group Members

- Zinah Ghulam
- Pramit Dutta
- Aurora Duran Gil
  
## Libraries Used

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- scikit-learn


