# DSC180A-Project-1-code

You need to check the https://github.com/Trustworthy-ML-Lab/CLIP-dissect/tree/main site and git clone it! Install Python (3.10)

Install Pytorch (tested with 1.12.0, also works with 2.0) and Torchvision >= 0.13 following instructions from https://pytorch.org/get-started/previous-versions/

Install remaining requirements using pip install -r requirements.txt

Download the Broden dataset (images only) using bash dlbroden.sh

(Optional) Download ResNet-18 pretrained on Places-365: bash dlzoo_example.sh

We do not provide download instructions for ImageNet data, to evaluate using your own copy of ImageNet validation set you must set the correct path in DATASET_ROOTS["imagenet_val"] variable in data_utils.py

PLEASE RUN "layer 1.ipynb" FIRST AND OTHERS CONTINUOUSLY!
