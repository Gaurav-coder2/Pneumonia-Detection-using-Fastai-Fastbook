# Pneumonia-Detection-using-Fastai-Fastbook

Pneumonia is a life-threatening infectious disease affecting one or both lungs in humans. According to the World Health Organization (WHO), one in three deaths in India is caused due to pneumonia. However, the early diagnosis and detection can provide a significant chance for correct treatment and survival measures. Deep Learning techniques during the last few decades had tremendous impact on various fields be it image recognition or speech recognition. Obviously, this technology is also highly relevant for medical imaging. There is lack of data availability in medical data since some of the medical data is subjected to patient privacy issues while the outbreak of a new disease also arises the same issue. Current trend in deep learning technique involves training a model over a large number of data and then exposing the same model for testing purposes but this convention might not hold against real world application where uncertainty is common syndrome. Thereby the proposed method, where the use of Transfer learning technique serves a multi prong solution, need not require data from the same feature space. Particularly training a large CNN architecture (ResNet50) over a large ImageNet Dataset then transferring the weights of initial layer and fine-tuning the last layers will result in a higher precision and recall value and faster performance in terms execution time of algorithms as compared to existing methods. In this work, the collected dataset is passed through seven different preprocessing steps before it is fed to the ResNet-50 module, in order to improve the validation and classification accuracy of the proposed model and achieve remarkable test accuracy. The same methodology/architecture will also hold good for any detection and localization of abnormality in Medical Images (e.g. classification and detection of Covid-19) with consistent performance which involves even multi-class classification problems.

**Dataset used:**
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia  The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

**Architecture:**

![Architecture croped](https://user-images.githubusercontent.com/58482510/116966832-a5cf5180-acce-11eb-8a89-28ba4388257f.jpg)

**Team members:**
1 [NehaBhujbal222](https://github.com/nehabhujbal222)
