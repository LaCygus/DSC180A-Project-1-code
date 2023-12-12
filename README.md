# DSC180A Project 1 Code Setup

## 1. Clone the Repository

Head to the [CLIP-dissect GitHub repository](https://github.com/Trustworthy-ML-Lab/CLIP-dissect/tree/main) and clone it to your local machine:

```bash
git clone https://github.com/Trustworthy-ML-Lab/CLIP-dissect.git
2. Install Python and Dependencies
Make sure you have Python 3.10 installed. If not, download and install it from the official Python website.

Install PyTorch (tested with 1.12.0, also works with 2.0) and Torchvision >= 0.13. Follow the instructions on the PyTorch website for installation.

Install the remaining requirements using:

bash
Copy code
pip install -r requirements.txt
3. Download Broden Dataset
Execute the following bash command to download the Broden dataset (images only):

bash
Copy code
bash dlbroden.sh
4. Optional: Download Pretrained Model
If you want to use a pretrained ResNet-18 model on Places-365, run the following bash command:

bash
Copy code
bash dlzoo_example.sh
5. Note on ImageNet Data
We do not provide instructions for downloading ImageNet data. If you have your own copy of the ImageNet validation set, set the correct path in the DATASET_ROOTS["imagenet_val"] variable in data_utils.py.

6. Run Notebooks
Start by running "layer 1.ipynb" first and continue with the other notebooks in sequence.

kotlin
Copy code

Feel free to use or modify this Markdown version as needed.
