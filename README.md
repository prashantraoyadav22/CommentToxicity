# CommentToxicity

Engineered a high-accuracy deep learning model in Python for comment toxicity detection, leveraging advanced algorithms to enhance text classication and analysis.
This is a deep learning-based Gradio web app that detects toxic comments using an LSTM model trained on a Kaggle dataset.

## Tech Stack
- Python
- TensorFlow
- Gradio
- Hugging Face Spaces

- Created TensorFlow datasets with caching, shuffling, batching, and prefetching, reducing data processing time by 50%.
- Implemented fully connected layers for feature extraction using TextVectorization, Embedding, and Bidirectional LSTM, increasing model accuracy by 20%.
- Compiled the model with BinaryCrossentropy loss and Adam optimizer, achieving a training accuracy of 92% and a reduction in loss by 30%.
- Trained the model, plotted training history, and achieved a precision of 89% and recall of 87% on the test set.
- Deployed the model using Gradio, enabling real-time comment toxicity scoring with a response time under 200 milliseconds.

Example 
![image](https://github.com/user-attachments/assets/420c9495-1086-4874-9b10-474c6cdc8e0b)
