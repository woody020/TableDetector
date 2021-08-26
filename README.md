# TableDetector

TableDetector : Deep Learning Model for end-to-end table table detection from Scanned Document Images.

TableDetector is inspired TableNet, a IDCAR 2019 paper proposed by a research team from TCS.

[__Paper__](https://arxiv.org/abs/2001.01469)


## How to run

Requirements:
tensorflow2.2.0
1. Download the Marmot Dataset from the link given.
2. I have used google drive to work with the dataset. Upload the Marmot dataset on your Google Drive and create two folders as column_mask and table_mask in same directory
3. data_preprocesses/generate_mask.py generates the column and table masks for the dataset.
4. generate mask has been included in the TableNet.ipynb so no need to run it again.
5. Run the TableNet.ipynb in Google Colab or Jupyter Notebook.
6. Train the model, check for predictions, then save the model on drive. Download the model.zip file on your system.

##Challenges
* Requires a very decent System with a good GPU for accurate result on High pixel images. 

## Dataset
Download the dataset provided in paper : [Marmot Dataset](https://drive.google.com/drive/folders/1QZiv5RKe3xlOBdTzuTVuYRxixemVIODp). 
