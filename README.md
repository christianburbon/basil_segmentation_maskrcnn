# Using Image Segmentation in Determining the Readiness of Sweet Basil Seedlings for Plant Growing
This repo is for the results and codes used in assessing readiness for sweet basil seedlings

## Installationg and Setup
To be able to run the code, the environment needs to be setup properly for Mask R-CNN. Please follow the instructions from https://www.immersivelimit.com/tutorials/mask-rcnn-for-windows-10-tensorflow-2-cuda-101 to install all the necessary pre-requisites.

## Running the codes

### Dataset
Use these to skip steps 1 and 2
* Images can be found here https://drive.google.com/drive/folders/1nga2TyWUemc9DHM6kIWc-S-rYOi73gq8?usp=sharing
* Annotations can be found in the annotations folder. Each of the subfolders mentioned below should have a json file that has either *train* or *val* label which are used for train, and validation sets respectively.
  * For leaf and plant related annotations. go to folder *leaf and plant*. It should contain a folder names final_annotaitons where the following is found
    * leaf and plant
    * leaf only
    * plant only
  * For plant ready or not ready. go to folder *ready and not ready*. It should contain a folder named final_annotations


### Step 1: Run the data_preloader_1.py
