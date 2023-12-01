# Signature-Verification
Here we have uploaded cleaned dataset to downlaod for refrence. 

# Model 1 : Signature Pro 2.o
Step 1: Model Architecture Selection
Our initial approach involved the selection of the MobileNetV2 architecture as the foundation
for our model. This choice was underpinned by its proven capabilities in image classification
tasks.

Step 2: Finetuning Implementation
The second phase comprised the implementation of the Finetuning technique. Leveraging
MobileNetV2 as the base model, we introduced additional dense layers to enhance the model’s
performance. The achieved overall accuracy was commendable, yet the validation accuracy
raised concerns at 73

Step 3: Hypothesis Testing Through Additional Layers
In response to the sub-optimal validation accuracy, we tested the hypothesis that further
training through additional layers could address the issue. However, the validation accuracy
remained stagnant at 73%, prompting a deeper investigation.

Step 4: Depth Enhancement and Unanticipated Results
In an attempt to enhance the model’s learning capacity, we explored increasing its depth.
Contrary to expectations, the validation accuracy remained unchanged at 73%, signaling a
potential issue within the dataset.

Step 5: Dataset Analysis and Anomaly Identification
Conducting a meticulous analysis of classes with low validation accuracy, we identified images
in poor conditions and lacking visual consistency within classes. This observation pointed
towards dataset anomalies as the root cause of our challenges.

Step 6: Dataset Cleansing and Refinement
In response to the identified anomalies, we initiated the creation of a refined dataset. This
involved the exclusion of classes exhibiting corrupted or inconsistent images, ensuring a more
robust and reliable dataset for subsequent model training.

Step 7: Model Retraining on Refined Dataset
Taking our refined dataset into account, we conducted another round of model training.
Remarkably, this iteration achieved an accuracy surpassing 98%, with validation accuracy
reaching an impressive 100%. Minor underfitting, attributed to the sparse validation dataset,
was deemed acceptable.

Step 8: Model Validation and Confidence Boost
To validate the model’s efficacy, a random selection of images from a specific class was
employed. The model demonstrated flawless accuracy, correctly predicting all images within
the chosen class. This outcome instilled confidence in the model’s reliability and suitability
for diverse datasets.

Step 9: Creation of Preserved Refined Dataset
To safeguard the integrity of our refined dataset for future applications, we formally archived
the cleansed dataset. This strategic move ensures a consistent and dependable foundation
for subsequent model development and experimentation.

Step 10: Conclusion
The sequential progression through these steps reflects a methodical and iterative approach,
where each stage addressed specific challenges encountered in the pursuit of an optimized
and accurate image classification model.
