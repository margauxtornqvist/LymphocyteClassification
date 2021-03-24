# LymphocyteClassification
Multi-instance Level classification of images of lymphocytes

This project was done in the context of Kaggle competition (https://www.kaggle.com/c/3md3070-dlmi/overview)

<p align="center">
  <img src="https://user-images.githubusercontent.com/46713435/112282962-e8d9e600-8c87-11eb-9f60-e6de582c7c1d.jpg" />
</p>

This work focuses on predicting lymphocyte diagnosis for a patient given two types of data: lymphocyte microscopic images and clinical attributes such as age and lymphocyte concentration, by using deep learning methods. Convolutional neural networks are trained on bags of various size of microscopic images to extract meaningful features whereas a linear classifier is trained to predict the outcome from the clinical data. Moreover, we explore different ways of combining the outputs of each of these classifiers to predict the correct label for a given patient. We face the difficulties of multi-instance learning in a medical context, where even clinicians have variable consensus on the diagnosis. Finally our best results report a balanced accuracy of 78.96% on the private leaderboard. 

Lymphocytosis is a diagnosis characterized by lymphocyte count above 4.10^9/L. There are two forms of lymphocytosis: reactive and tumoral. The reactive form is most often due to an immune response to an infection or to stress. The tumoral form is due to leukemia, a lethal cancer attacking blood cells, and is therefore crucial to detect.  Clinicians  distinguish between the tumoral and reactive form by using their expertise on clinical data as well as images. However this technique, prone to error, brings them to realize additional clinical tests. Notably, flow cytometry, is the gold standard to detect with high accuracy the correct form of lymphocytosis. But this expensive and time consuming technique  can’t be done for every patient. Considering a tool which could automatically classify lymphocyte population based on visual assessment and clinical data would save time and money to many hospitals and cliniques. This work focuses on exploring deep learning techniques which could be used to design a tool to automatically classify patients with high accuracy into reactive or tumoral form of lymphocytosis. 
