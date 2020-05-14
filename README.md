# Depression-Detection-Through-Multi-Modal-Data

Conventionally depression detection was done through extensive clinical interviews, wherein the subject’s re-
sponses are studied by the psychologist to determine his/her mental state. In our model, we try to imbibe this approach
by fusing the 3 modalities i.e. word context, audio, and video and predict an output regarding the mental health of
the patient. The output is divided into a binary yes/no denoting whether the patient has symptoms of depression. We’ve built a deep learning model that fuses these 3 modalities, assigning them appropriate weights, and thus
gives an output.

# Using the files:
Please make a copy of the drive folder (https://drive.google.com/drive/u/1/folders/1VhRO2phIYBkFjvp2EZdnUE1vTx4ILSal, the folder has been shared with the TAs) to your main my-drive folder. The files on this github repository should work if the dataset folder is copied in the correct location. Please run the files on *Google Colab* for easiest usage. The main file has not been created as our work is segmented, and is easier to read as seperate files. The dataset was never downloaded locally due to it's large size and other computational limitations. Thus the dataset has not been added to the submitted file.

# Files:
* Dataset.ipynb: : The code snipets used to obtain from the DAIC server, unzip them and arrange them in a manner we saw fit for easy implementation.
* SVM&RF_Text.ipynb: The code snipets used to run the SVM and RF models on the text modality.
* SVM&RF_Video.ipynb: The code snipets used to run the SVM and RF models on the video modality.
* SVM&RF_Audio.ipynb: The code snipets used to run the SVM and RF models on the audio modality.
* SVM&RF_CombinedModalities.ipynb:The code snipets used to run SVM and RF models on all 3 modalities with late fusion.
* Rf_prune.ipynb: Implementation of pruneing on RFs. 
* CNN_Audio.ipynb: The code snipet used to run CNN on the audio features. 
* CNN_Text.ipynb: The code snipet used to run CNN on the text features. 
* CNN_Video.ipynb: The code snipet used to run CNN on the video features. 
* LSTM_Without_Gating_Sentence_Level.ipynb: Implementation of LSTM on all 3 modalities combined without gating, at the sentence level. 
* LSTM_With_Gating_Sentence_Level.ipynb: Implementation of LSTM on all 3 modalities combined with gating, at the sentence level. 
* LSTM_WITH_GATING_WordLevel.ipynb: Implementation of LSTM on all 3 modalities combined with gating, at the word level. 
* BiLSTM_WordLevel.ipynb: Implementation of BiLSTM on all 3 modalities. 
