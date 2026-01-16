Overview

This project implements graph-based image segmentation using the Felzenszwalb–Huttenlocher algorithm. The goal is to segment images while preserving strong edges and natural boundaries.

# Tech Stack

Language: Python

Dataset: BSDS500

Evaluation Metrics: Adjusted Rand Index (ARI)

# Features

Edge-preserving image segmentation

Efficient graph-based algorithm implementation

Quantitative evaluation of segmentation quality

Parameter sensitivity and runtime analysis

# Algorithm Workflow
Represent image pixels as nodes in a graph

Assign edge weights based on pixel similarity

Iteratively merge regions based on internal differences

Produce segmented output with clear boundaries

# Evaluation

Used Adjusted Rand Index (ARI) for segmentation quality

Analyzed impact of parameter tuning on accuracy and runtime

Identified computational bottlenecks and optimization areas

# Future Enhancements

GPU acceleration for large images

Comparison with deep learning-based segmentation

Interactive visualization of segmentation steps

https://github.com/REBECCA-SHAH/Image-Segmentation-Rebecca/blob/main/WhatsApp%20Image%202025-08-03%20at%2016.11.32_d02612b1.jpg

