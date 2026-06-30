# The Statistical & Hand-Crafted Feature Descriptor Era (~1990s–2011)

## Overview
This era shifted focus from global geometric models to localized statistical descriptors. Engineers designed local feature extractors invariant to scale, rotation, and illumination.

## Key Concepts
- **SIFT (Scale-Invariant Feature Transform):** Detects stable keypoints across scale spaces.
- **HOG (Histograms of Oriented Gradients):** Counts occurrences of gradient orientations in localized portions of an image.
- **Viola-Jones Framework:** Uses Haar-like features and AdaBoost classifiers for real-time face detection.

## Diagram
```mermaid
flowchart LR
    A[Input Image] --> B[Scale-Space Extrema Detection]
    B --> C[Keypoint Localization]
    C --> D[Orientation Assignment]
    D --> E[Keypoint Descriptor Generation]
    E --> F[SVM / Classifier Matching]
```

## References
- Lowe, D. G. (1999). *Object recognition from local scale-invariant features*.
- Dalal, N., & Triggs, B. (2005). *Histograms of oriented gradients for human detection*.
- Viola, P., & Jones, M. (2001). *Rapid object detection using a boosted cascade of simple features*.
