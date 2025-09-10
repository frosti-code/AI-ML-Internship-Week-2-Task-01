🎯 Objective

To fine-tune a transformer-based model (BERT) to classify news headlines into topic categories using the AG News Dataset.

📂 Dataset

AG News Dataset from Hugging Face Datasets

Contains 4 news categories:

World

Sports

Business

Sci/Tech

Each sample includes a:

Title (used as input text)

Label (used as class target)

🔧 Steps Performed

Dataset Loading and Preprocessing

Loaded dataset using load_dataset("ag_news")

Tokenized using BertTokenizerFast from bert-base-uncased

Truncated and padded input sequences

Model Initialization

Used BertForSequenceClassification with 4 output labels

Configured training using TrainingArguments and Trainer

Model Training

Fine-tuned on training set

Evaluated on test set using:

Accuracy

F1-score

Deployment

Built an interactive demo using Gradio

Users can input a headline and get predicted topic in real-time

📈 Evaluation Metrics
Metric	Value (Example)
Accuracy	✅ Implemented
F1-Score	✅ Implemented

Note: Metrics were calculated using the Hugging Face Trainer evaluation API.

🧪 Technologies Used

Python 3.x

Hugging Face Transformers

Datasets (AG News)

PyTorch

Gradio (for UI)

scikit-learn (for evaluation)

💡 Key Features
Feature	Implemented
BERT fine-tuning on AG News	✅
Text tokenization and batching	✅
Model evaluation (F1 & Accuracy)	✅
Gradio deployment for demo	✅
🚀 Skills Gained

Working with transformer-based NLP models

Text classification using pre-trained models

Evaluation using industry-standard metrics

Lightweight UI deployment with Gradio
Author : 
Muhammad Mustaqeem Javed - AI/ML Intern

End-to-end ML/NLP pipeline design
