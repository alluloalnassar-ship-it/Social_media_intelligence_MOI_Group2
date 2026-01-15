# Social_media_intelligence_MOI_Group2


## Project Summary

This project focuses on Arabic social media text classification to detect offensive vs. non-offensive content using two different modeling approaches: a transformer-based classifier and a fine-tuned large language model.

## Implemented Models

1) AraBERT Classifier
	•	Model: AraBERT (Arabic BERT)
	•	Dataset: Arabic.csv (labeled)
	•	Data split: Train / Validation / Test
	•	Task: Binary classification (offensive vs. not)
	•	The trained model is used to generate predictions on real Twitter data (merged_twitterdata.csv).

2) Qwen3 Fine-Tuned LLM
	•	Model: Qwen3-4B (quantized)
	•	Training approach:
	•	Prompt-based supervised fine-tuning
	•	Text generation labels (offensive / not)
	•	Dataset: Arabic.csv
	•	Class imbalance handled during training
	•	LoRA adapters used for efficient fine-tuning
	•	Predictions generated for real Twitter data.

## Evaluation
	•	Models evaluated using accuracy, precision, recall, and F1-score.
	•	Additional comparison performed using human-labeled Twitter data:
	•	merged_twitterdata with human classification.csv

  ## Files
	•	Social_media_intelligence_update3_MOI_NewCode.ipynb – AraBERT training and inference
	•	Qwen3_Arabic_Offensive_Train_Clean.ipynb – Qwen3 fine-tuning and inference
	•	Arabic.csv – Labeled training dataset
	•	merged_twitterdata.csv – Real unlabeled data
	•	merged_twitterdata with human classification.csv – Human annotations

## Notes
	•	All experiments are conducted on Arabic text.

  ## Group 2 – Social Media Intelligence Project

   Raghad Ghawa - Allulo Alnassar - Hissah Alsuqayh -  Amjaad aldawsari - Alanoud Aleisa  - Nehal Alhablani
