# MRI Data Visualization

## Objective
The goal of this project is to demonstrate how to read, parse, and visualize medical imaging data stored in **NIfTI (`.nii`)** and **DICOM (`.dcm`)** formats using Python. Libraries such as `nibabel`, `pydicom`, and `matplotlib` are used to explore both low-level and high-level operations on 3D volumetric medical data.

> **All detailed answers, code implementations, and discussions are included in the notebook:** `mri_data_visualisation.ipynb`

---

## Contents of the Notebook

The notebook addresses the following key questions and tasks:

1. **How can we read and load NIfTI and DICOM files in Python?**
   - Load NIfTI files using `nibabel`.
   - Load individual DICOM slices using `pydicom`.

2. **What is the internal structure and metadata of these formats?**
   - Explore fields such as shape, affine matrix, voxel spacing, and metadata tags.

3. **How do we stack DICOM slices into a 3D volume?**
   - Sort DICOM slices and stack them into a 3D NumPy array.

4. **How can we visualize anatomical planes from a 3D image volume?**
   - Generate axial, sagittal, and coronal views using `matplotlib`.

5. **How do we interpret image orientation?**
   - Use affine matrix and orientation tags to understand image alignment.

6. **What are the key differences between DICOM and NIfTI?**
   - Compare formats based on intended use, metadata structure, and file conventions.

---

## Libraries

- `nibabel`
- `pydicom`
- `matplotlib.pyplot`
- `numpy`
- `ImageIO`
- `SciPy`

---

## Note

This repository contains the final notebook which is `mri_data_visualisation.ipynb` and also the rough work kaggle notebook as I have mentioned in the documentation in the code.
