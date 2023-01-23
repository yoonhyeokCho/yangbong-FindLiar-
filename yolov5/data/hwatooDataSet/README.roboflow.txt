
hwatoo model - v1 2023-01-23 4:34pm
==============================

This dataset was exported via roboflow.com on January 23, 2023 at 7:36 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 24 images.
Hwatoo are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random rotation of between -15 and +15 degrees
* Random shear of between -27° to +27° horizontally and -14° to +14° vertically
* Random brigthness adjustment of between -40 and +40 percent

The following transformations were applied to the bounding boxes of each image:
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically


