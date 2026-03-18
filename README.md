# VLM Mini Workshop (Beginner Friendly)

This repository contains a simple notebook for teaching the core idea of Vision-Language Models (VLMs) in about 1 hour.

The notebook uses a small public Kaggle dataset and two easy demos:
1. Image captioning (image -> text)
2. Visual question answering (image + question -> answer)

## Files

- vlm_mini.ipynb: Main workshop notebook
- other_resources/: Legacy files from earlier project version (not required for this mini workshop)

## How to run the workshop

Open the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rajashikdatta/vlm-mini/blob/main/vlm_mini.ipynb)

Set your Colab Secrets (click the key icon in the left sidebar):

| Secret Name | Where to get it |
|---|---|
| KAGGLE_USERNAME | kaggle.com -> Account -> API |
| KAGGLE_KEY | Same Kaggle API token page |
| HF_TOKEN | huggingface.co/settings/tokens |

Change runtime to T4 GPU: Runtime -> Change runtime type -> T4 GPU

Run cells top to bottom - no uploads, no manual steps.

## Dataset used

- Kaggle dataset: https://www.kaggle.com/datasets/alxmamaev/flowers-recognition
- Notebook behavior: downloads dataset and samples a tiny subset for fast execution

## Suggested 60-minute teaching flow

1. 0-10 min: What is a VLM, and where image + text models are used.
2. 10-20 min: Colab setup and Kaggle secrets.
3. 20-35 min: Run captioning demo and discuss outputs.
4. 35-50 min: Run image Q&A demo and compare model answers.
5. 50-60 min: Student mini activity and wrap-up.

## Notes for instructors

- This is a concept-first workshop notebook, not a training pipeline.
- No model fine-tuning is required.
- Keep discussion centered on strengths, limitations, and bias in model outputs.

## License and model references

- BLIP caption model: Salesforce/blip-image-captioning-base
- BLIP VQA model: Salesforce/blip-vqa-base
