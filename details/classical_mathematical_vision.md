# Classical Mathematical & Edge-Based Vision

## Overview
Classical edge-based vision relies on spatial gradient calculations and analytical geometry to identify structural elements in an image canvas.

## Key Concepts
- **Gradient Operators:** Computing horizontal and vertical intensity differences (Sobel/Prewitt).
- **Canny Edge Detector:** Incorporates Gaussian smoothing, gradient computation, non-maximum suppression, and hysteresis thresholding.
- **Hough Transform:** Votes in a parameter space to link isolated edges into continuous analytical shapes (lines, circles).

## Diagram
```mermaid
flowchart LR
    A[Input Image] --> B[Gaussian Noise Filter]
    B --> C[Sobel Gradient Calculation]
    C --> D[Non-maximum Suppression]
    D --> E[Hysteresis Thresholding]
    E --> F[Edges Detected]
```

## References
- Sobel, I. (1968). *An Isotropic 3x3 Image Gradient Operator*.
- Canny, J. (1986). *A Computational Approach to Edge Detection*.
