# 3D-unet
Source code for the chronic stroke lesion segmentation paper. 


To replicate the results, install the nnUnet framework (https://github.com/MIC-DKFZ/nnUNet).
Download the pretrained models from here: https://www.dropbox.com/s/ha2co8b7vleqkr0/trainedModelsATLASv2_ResidualUNet.zip?dl=0

**To run the inference on the pretrained models**

Run ensembling to predict from several configurations with the following command:

```bash
nnUNet_ensemble -f FOLDER1 FOLDER2 ... -o OUTPUT_FOLDER -pp POSTPROCESSING_FILE
```

