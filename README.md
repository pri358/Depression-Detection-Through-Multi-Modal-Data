# Depression-Detection-Through-Multi-Modal-Data

Conventionally depression detection was done through extensive clinical interviews, wherein the subject’s re-
sponses are studied by the psychologist to determine his/her mental state. In our model, we try to imbibe this approach
by fusing the 3 modalities i.e. word context, audio, and video and predict an output regarding the mental health of
the patient. The output is divided into different levels to take into consideration the level of depression of the sub-
ject. We’ve built a deep learning model that fuses these 3 modalities, assigning them appropriate weights, and thus
gives an output.

Files:
* Dataset.ipynb: The code snipets used to obtain from the DAIC server, unzip them and arrange them in a manner we saw fit for easy implementation.
* MCA_Audio.ipynb: The code snipets used to run the SVM and RF models on the audio modality.
* MCA_Video.ipynb: The code snipets used to run the SVM and RF models on the video modality.
* MCA_Text.ipynb: The code snipets used to run the SVM and RF models on the text modality.
* Combine.ipynb: The code snipets uused to run SVM and RF models on all 3 modalities with late fusion.
* Rf_prune.ipynb: The code snipets used to prune the RF obtained from running RF on the late fusion of 3 modalities.
* CNN_MCA_Video.ipynm: The code snipet used to run CNN on the video features. 
* CNN_Audio.ipynb: The code snipets used to run CNN on the audio features. 
* MCA_CNN_Text.ipynb: The code snipets used to run CNN on the text features. 
