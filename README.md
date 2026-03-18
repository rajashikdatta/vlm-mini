# VLM Mini Workshop (Beginner Friendly)

This repository contains a simple notebook for teaching the core idea of Vision-Language Models (VLMs) in about 1 hour.

The notebook uses a small public Kaggle dataset and two easy demos:
1. Image captioning (image -> text)
2. Visual question answering (image + question -> answer)

## Files

- paddy_vlm_workshop.ipynb: Main workshop notebook
- other_resources/: Legacy files from earlier project version (not required for this mini workshop)

## Open in Colab

Open the notebook directly from your GitHub repository:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rajashikdatta/vlm-mini/blob/main/paddy_vlm_workshop.ipynb)

## Workshop setup (for students)

1. Open notebook in Google Colab.
2. Set runtime to GPU:
   Runtime -> Change runtime type -> T4 GPU
3. Add Colab secrets from the key icon:
   - KAGGLE_USERNAME
   - KAGGLE_KEY
4. Run all cells from top to bottom.

Kaggle API keys are available at:
https://www.kaggle.com/settings/account

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
