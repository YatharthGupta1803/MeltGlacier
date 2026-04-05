# 🌍 Glacier Water Segmentation using Image Processing

This mini project explores how computer vision and image processing can be applied to analyze environmental changes using real-world satellite data.

Inspired by the Introduction to Image Processing course by MathWorks (Coursera), the project focuses on detecting and quantifying glacial meltwater changes over time.

# 📌 Problem Statement

Glaciers are rapidly changing due to climate change. One visible indicator is the increase in surface meltwater.

This project aims to:

Segment water bodies from satellite images
Compare changes across time (2018 vs 2020)
Estimate the increase in meltwater spread
#🛰️ Dataset
Source: Landsat 8 satellite imagery
Timeframes:
January 2018
January 2020
#⚙️ Methodology

The workflow follows a structured image processing pipeline:

1. Image Preprocessing
Convert images into analyzable format
Normalize and prepare for segmentation
2. Water Segmentation
Apply thresholding techniques
Use color-based segmentation (RGB space)
Extract water regions as binary masks
3. Refinement
Utilize MATLAB’s Color Thresholder App
Analyze histograms to fine-tune thresholds
4. Change Analysis
Compare segmented outputs across years
Estimate increase in water-covered regions
📊 Results
Clear increase in segmented water regions from 2018 to 2020
Visual confirmation of glacial melt progression
Demonstrates how simple image processing techniques can reveal climate patterns
🧠 Key Learnings
Image segmentation (thresholding & masking)
Working with real-world satellite data
Converting raw imagery into meaningful insights
Practical use of MATLAB for computer vision tasks
🛠️ Tech Stack
MATLAB
Image Processing Toolbox
Landsat Satellite Data
