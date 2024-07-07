# PS-exposure
README（Quantification of PS exposure）

Overview
This MATLAB code is designed for the analysis of confocal fluorescence time-lapse imaging data. The primary objective of this code is to quantify the fluorescence intensity on the cell membrane, which is an indicator of phosphatidylserine (PS) externalization in cells. PS externalization is a marker for CaPLSase function.

Features
Data Loading: The code loads time-lapse imaging data in standard formats.
Image Processing: It processes images to identify and segment cell membranes.
Fluorescence Quantification: It measures fluorescence intensity on the cell membrane over time.
Statistical Analysis: It provides statistical analysis of the fluorescence intensity to indicate PS externalization.
Requirements
MATLAB R2021a or later
Image Processing Toolbox
Statistics and Machine Learning Toolbox

Usage
Data Preparation: Ensure your time-lapse imaging data is in TIFF format.
Loading Data: Use the load Images function to load your imaging data.
Fluorescence Quantification: The quantify Fluorescence function will measure the fluorescence intensity.
Statistical Analysis: Use the analyze Fluorescence function to perform statistical analysis on the quantified data.

Notes
Ensure that your images are properly pre-processed (e.g., noise reduction, contrast enhancement) before running the analysis.
The statistical analysis results can be used to interpret the extent of PS externalization over time.

Contact
For any questions or issues, please contact guohs@szbl.ac.cn.
