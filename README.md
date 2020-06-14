# MultiFace_FaceMaskDetector
Detect mask v/s no-mask on faces in an image using a combination of a openCV based face detector DNN and a trained keras model for mask detection.  Model and Google Colab ipynb included. 

1) Upload mask_detector.zip file to google colab;
2) Upload ipynb to Google Colab or "open in colab" using the Colab Chrome plugin 
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/menonpg/MultiFace_FaceMaskDetector/blob/master/MaskDetector.ipynb)
3) The code outputs a "result.png" file with the detected faces and a green / red mask based on whether a mask is detected. 
   
![Sample Google Colab session](screenshots/ColabScreenshot.PNG)

Trained models for this example come from ![bm777](https://github.com/bm777/humanface-mask-detector)

