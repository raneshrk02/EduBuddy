# Edubuddy: Finetuning GPT-2 on NCERT Textbooks

This project demonstrates the finetuning of OpenAI's GPT-2 language model using textual data extracted from NCERT (National Council of Educational Research and Training) books. The goal is to create an educational language model with domain-specific understanding tailored to Indian school-level curriculum content.

---

## Project Structure

- `NCERT_Book_download.ipynb`  
  Script to automatically download NCERT books in PDF format from the official website.

- `NCERT_Data_cleaning.ipynb`  
  Pipeline to extract and clean text data from downloaded PDFs, removing headers, footers, and irrelevant content.

- `Model_Finetuning.ipynb`  
  Notebook that prepares the dataset and finetunes the GPT-2 model using Hugging Face Transformers and PyTorch.

---

## Features

- Uses real academic data from NCERT across various grades and subjects.
- Implements custom text cleaning for high-quality dataset preparation.
- Finetunes GPT-2 for education-focused text generation.
- Enables downstream educational applications like tutoring bots or quiz generation.

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ncert-gpt2.git
cd ncert-gpt2
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Notebooks in Order

1. `NCERT_Book_download.ipynb` – Download the books
2. `NCERT_Data_cleaning.ipynb` – Clean the text
3. `Model_Finetuning.ipynb` – Train the GPT-2 model

---

## Tech Stack

* Python 3.x
* PyTorch
* Hugging Face Transformers
* Tqdm, Pandas, Regex
* PyMuPDF (for PDF text extraction)

---

## Future Work

* Evaluate model performance on academic question-answering.
* Expand dataset to include state board textbooks.
* Deploy the model as an interactive chatbot.