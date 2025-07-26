# XLM-RoBERTa Sentiment Analysis on Amazon Fine Food Reviews

This repository contains a Jupyter Notebook that fine-tunes the **XLM-RoBERTa** transformer model to perform sentiment classification on the **Amazon Fine Food Reviews** dataset. The model was trained using the Hugging Face `transformers` library and evaluated using standard classification metrics.

---

## 📘 Description

The goal of this project is to train a transformer-based model to classify reviews as **positive**, **neutral**, or **negative** based on their content. The dataset used includes thousands of customer reviews of food products from Amazon.

We used the multilingual but English-capable **XLM-RoBERTa-base** model for its robustness to varied linguistic patterns, which are common in customer reviews.

---

## 📊 Results

| Metric         | Value              |
|----------------|--------------------|
| Accuracy       | 0.93               |
| Precision      | 0.9675             |
| Recall         | 0.9492             |
| F1 Score       | 0.9583             |
| Training Time  | 703.61 seconds     |
| Testing Time   | 13.57 seconds      |

---

## 📁 Files

- `XLM-RoBERTa_Sentiment_Analysis.ipynb`: Jupyter notebook containing full code for training and evaluation.
- `requirements.txt` (optional): Can be added to list all packages used.

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install transformers datasets scikit-learn pandas torch
   ```

4. Run the notebook in Jupyter or Colab:
   - Open the `.ipynb` file.
   - Execute all cells step by step.

---

## 📦 Dataset

- Dataset used: **Amazon Fine Food Reviews**
- If not already provided, you can download it from [Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews) or use any cleaned version in CSV format with `text` and `label` columns.

---

## 🤖 Model

- Model used: `xlm-roberta-base` from Hugging Face
- Fine-tuned using Hugging Face's `Trainer` API

---

## 📄 License

This project is licensed under the MIT License.

```
MIT License

Copyright (c) 2025 Haqeeq Ahmed

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights   
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell      
copies of the Software, and to permit persons to whom the Software is          
furnished to do so, subject to the following conditions:                       

The above copyright notice and this permission notice shall be included in     
all copies or substantial portions of the Software.                            

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR     
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,       
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE    
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER         
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN      
THE SOFTWARE.
```

---

## 🙋‍♂️ Author

**Haqeeq Ahmed**  
Master’s Student in Computer Science & Technology  
Specialized in Sentiment Analysis and NLP with LLMs

---

## ⭐ Acknowledgments

- Hugging Face for the amazing `transformers` library.
- The contributors of the Amazon Fine Food Reviews dataset.
