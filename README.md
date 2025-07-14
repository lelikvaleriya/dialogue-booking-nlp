# dialogue-booking-nlp

A generative dialogue model for booking flights and hotels, fine-tuned on a filtered subset of the [Schema-Guided Dialogue (SGD)](https://huggingface.co/datasets/GEM/schema_guided_dialog) dataset using the T5-small architecture.

---

## 🗂 Project Structure

```
Booking Dialogue Generator
├── LLM for booking train.py           # Training the model. Version with outputs can be found [here on Colab](https://colab.research.google.com/drive/11HJLTroEz1EGRg6yGFyWi3AMrjrXLsHL#scrollTo=5CDFxgXyKiOu)
├── LLM for booking evaluation.ipynb      # Evaluation notebook with BLEU & ROUGE  
├── generated_examples_for_manual_check.csv  # Hand-picked examples for manual evaluation  
├── report.pdf                            # Final project report  
├── README.md                             # This file  
```
