# 498sm_final
Final for ECE 498 SM
Nathan Cueto - Fengmao Zheng

# Proposal
We propse some changes to further optimize the Mask-RCNN COCO performance 

* Dataset: Reduce the 2014 dataset to only include relevant, outdoor images. Also, reduce number of classes from 80 to 12 classes.
Lesser classes should mean a smaller network.

* Backbone: Smaller network should allow for the lower throughput of a cheaper feature-extraction backbone - resnet50.

* Image augmentation: Implement various image augmentation techniques for training

* Evaluation: Interpolate framerate: Only run on a fraction of input frames to prevent redundant inferences.

# Code
Most code is in samples/final/coco.py. We also used the .ipynb notebooks for further verification during the training process.

The training notebook is linked as 498sm_train_final.ipynb.

Results are posted on YouTube here:
