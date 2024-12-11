Japanese Word Segmentation and POS Tagging
This repository contains the training code and datasets for our project on Japanese word segmentation and part-of-speech (POS) tagging using various deep learning models.

Overview
We experimented with three models to tackle the task of Japanese word segmentation and POS tagging:

Fine-tuning BERT
Initially, we fine-tuned the BERT model. However, its performance was suboptimal, with an accuracy of less than 50%.

BERT + CRF
To improve performance, we added a Conditional Random Field (CRF) layer on top of the BERT model. This approach achieved a significant improvement, reaching an accuracy of 60%.

BiLSTM + CRF
Finally, we implemented a BiLSTM + CRF model, which outperformed the previous methods. This model achieved an impressive accuracy of 92% on the test dataset.

File Structure
Fine-tuning BERT.ipynb: Code for training the fine-tuned BERT model.
BERT+CRF.ipynb: Code for training the BERT + CRF model.
output-train.json: Training dataset output.
output-val.json: Validation dataset output.
output-test.json: Test dataset output
