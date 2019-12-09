# Mask Region Convolutional Neural Network

This is a stripped down version of [The FAIR Mask R-CNN Implementation](https://github.com/matterport/Mask_RCNN.git). There were some problems with using the jupyter notebooks and Keras multiprocessing on Windows-10 64bit machines.

# Steps to reproduce
1. Clone this repo into a fresh virtual environment.
```git clone https://github.com/FletcherFT/mrcnn-playground.git```
2. Install the requirements.txt file.
```pip install -r requirements.txt```
2. (opt.) Install the optional-requirements.txt file, which contains the tensorflow-gpu package.
```pip install -r optional-requirements.txt```
3. Test the training script:
```python train_shapes.py```
