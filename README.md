# Garbage-Identification-and-Classification-using-Custom-model
## LINK FOR KAGGLE NOTEBOOK TO TRAIN MODELS:
- Transformer: 
## PYTHON PACKAGES REQUIREMENT:
- PyTorch (CUDA version is recommended)
- Matplot
- Numpy
- OpenCV
## INSTRUCTION
### If you train on your device, please start from here:
1. Due to Github limitation, please download all the classes folders with the link below, then unzip, copy and paste it into the `all_classes` folder (your directory should be ***all_classes/classes - Ex: all_classes/battery***). Link: https://www.kaggle.com/datasets/feyzazkefe/trashnet
2. Run `Training.py`
3. Check `models` folder to see if `Model.pth` available or not -> Then continue to step 5
### If you train your model using Kaggle, please continue from here:
4. Copy your downloaded model into the `models` folders
5. Run `Execute_Images.py` to identify and classify garbage in images (Using images / videos in `external` folder).
6. Run `Execute_Videos.py` to identify and classify garbage in videos or real-time webcam (Using images / videos in `external` folder).

