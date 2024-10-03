**Fine-tuned T5-small Model for Text Summarization**

**Project Overview**
This project involves fine-tuning a pre-trained T5-small model using a dataset from Hugging Face. The model has been optimized for the task of text summarization, specifically on the MeetingBank-QA-Summary dataset.

**Model Information**
Model used: T5-small
Dataset: MeetingBank-QA-Summary from Hugging Face
Task: Text Summarization
Evaluation Metrics: ROUGE Scores

**Steps to Fine-tune the Model**
Load the pre-trained T5-small model and tokenizer.
Use the MeetingBank-QA-Summary dataset from Hugging Face.
Fine-tune the model using the dataset with appropriate hyperparameters (e.g., learning rate, batch size).
Evaluate the model using ROUGE scores.

**Results**
After fine-tuning, the model shows improved performance in summarizing the dataset based on ROUGE metrics.

**How to Run**
To use the model, you can input text that needs summarization, and the fine-tuned model will return a summary.
