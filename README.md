Input Images: Brain MRI scans are fed into the pipeline.

ResNet Deep Learning Classifier Model: This model takes the MRI scans and classifies whether a tumor is present or not.

Output: If a tumor is not detected, the process ends and the patient is categorized as healthy.

ResUNet Segmentation Model: If a tumor is detected, this model refines the classification by predicting the tumor’s location on a pixel-by-pixel basis.

Data source: https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation
