Road segmentation in satellite imagery is a critical
task for urban planning and traffic management. The task
becomes challenging due to the varying conditions and complex
patterns of roads. In this study, we address the road segmentation
problem using deep learning techniques, specifically using
existing Segmentation Models Pytorch (SMP) U-Net, DeepLabV3
and a custom-built U-Net applied to the Massachusetts Roads
Dataset. U-Net, known for its efficiency in biomedical image
segmentation, and DeepLabV3, recognized for its effectiveness in
semantic segmentation and efference use of computational
resources, are employed to delineate roads in high-resolution
aerial images. Our approach includes comprehensive data
augmentation and specialized loss functions. We provide a
detailed comparative analysis of the three models, assessing their
performance in road detection accuracy and computational
efficiency. The results demonstrate that all models achieve high
accuracy, with U-Net showing effectiveness in finer details,
DeepLabV3 excelling in computational speed but failing in
accurately predicting results and the custom U-Net excelling in
both. This study contributes to the advancement of road
segmentation techniques and offers insights into the application
of deep learning in remote sensing.
![sample_pred_39](https://github.com/ogyousef/Road_segmentation/assets/83747441/cbb53c93-fe02-46cf-88f4-acdffa3fe504)
