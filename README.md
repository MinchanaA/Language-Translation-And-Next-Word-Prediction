# Language-Translation-And-Next-Word-Prediction

This project performs language translation and next-word prediction using NLP techniques. It processes text data, builds sequence models, and predicts translations or likely next words, enabling multilingual text generation and smart typing assistance.



# NLP Language Translation and Next-Word Prediction

This project performs **language translation** and **next-word prediction** using Natural Language Processing techniques. It uses the Hugging Face `transformers` library for text generation (GPT-2) and the `deep-translator` library for translation tasks.

---

## Features

✅ Translate text between languages using Google Translator API.  
✅ Predict next words in a sentence using a pre-trained GPT-2 model.  
✅ Interactive notebook for testing your own inputs.

---

## Requirements

Install Python dependencies:

```bash
pip install transformers deep-translator

How to Run the Project
1. Clone or Download the Project
Download or clone this repo to your machine.

2. Install Dependencies
In your terminal or Anaconda Prompt,
run:pip install transformers deep-translator

3. Open the Jupyter Notebook
jupyter notebook

4. Execute Cells
Run all notebook cells in order:

Import libraries.

Run translation examples:
from deep_translator import GoogleTranslator

translated = GoogleTranslator(source='en', target='fr').translate("Hello World!")
print(translated)
from deep_translator import GoogleTranslator

translated = GoogleTranslator(source='en', target='fr').translate("Hello World!")
print(translated)

