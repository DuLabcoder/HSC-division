# Cell Segmentation
The images of cells should first be converted to 8-bit TIFF format. The segmentation process is implemented in the `cell-segment.ipynb` notebook.

## Features
- Simple and effective workflow for cell segmentation.
- Designed for single-cell image analysis.
- Easy to customize and integrate with your own datasets.

<br>

# Image Convertion
Segmented single-cell images, comprising multiple channels such as the mask, fluorescent image, and brightfield image, can be batch-converted to 8-bit TIFF format efficiently using ImageJ.
   
    Process -> Batch -> Convert

<br>

# Calculation of Fluorescent Intensity of Daughter Cells
After converting the images to 8-bit TIFF format, you can calculate the fluorescent intensity of two daughter cells using the `FluoInt.ipynb` notebook.

<br>

# Calculation of Polarization Index of Single Cells
After converting the images to 8-bit TIFF format, you can calculate the polarization index of single cells using the `PolarIndex.ipynb` notebook.

<br>

# Requirements
- Python 3.8 and above
- Jupyter Notebook
- Required Python libraries (detailed in the notebook)
- P100 GPU

<br>

# License
Under MIT license. 

<br>

# Authors
- Feng Yiting fengyt22@mails.tsinghua.edu.cn
- Li Wenjing 
