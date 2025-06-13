
# Translator using BERT and Transformer 

This project is a Jupyter Notebook implementation of a text-to-text translation model using BERT and Transformer architectures. It demonstrates how to build a machine translation model that can translate sentences from one language to another using state-of-the-art NLP techniques.



## 🧠 Model Overview

The model is built using:
- BERT (Bidirectional Encoder Representations from Transformers) for capturing rich contextual representations.
- Transformer architecture for sequence-to-sequence translation.


## Installation ⬇️

Clone the repository:
```bash 
git clone https://github.com/yourusername/Text-Translation_BERT.git
cd Text-Translation_BERT
```
Create a virtual environment to isolate the project dependencies:
```bash
python -m venv Translator
```
Activate the virtual environment:

On Windows:
```bash 
Translator\Scripts\activate
```
On macOS/Linux:
```bash 
source healthcare-chatbot-env/bin/activate
```
 - Install dependencies:
Ensure you have Python installed, then install the required libraries:
```bash
pip install transformers datasets torch tqdm
```

Run the application:

```bash     
python Translator_Bert_Transformer
```

    
## ⚙️ Key Features
 - Tokenization and preprocessing using HuggingFace Transformers.

- Model training and evaluation on translation data.

- Visualization of translation results.