# Mask Region Convolutional Neural Network

This is a stripped down version of [The FAIR Mask R-CNN Implementation](https://github.com/matterport/Mask_RCNN.git). There were some problems with using the jupyter notebooks and Keras multiprocessing on Windows-10 64bit machines.

# Steps to reproduce
1. Clone this repo into a fresh python 3.6 virtual environment.

    ```git clone https://github.com/FletcherFT/mrcnn-playground.git```
2. Install the requirements.txt file.

    ```pip install -r requirements.txt```
    
    **Note** If you receive an error from pip when trying to install the `shapely` module, install it manually either from [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#shapely), or using the .whl included in this repo:
    
    ```pip install .\extras\Shapely-1.6.4.post2-cp36-cp36m-win_amd64.whl```
    
    Then try the first command in this step again. Hopefully it should work on your system :)
3. (opt.) Install the optional-requirements.txt file, which contains the tensorflow-gpu package.
    
    ```pip install -r optional-requirements.txt```
4. Test the training script:

    ```python train_shapes.py```
