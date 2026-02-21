# 🌾 PaddyVLM — Workshop Repository

This repository contains the **expert knowledge resources** for the PaddyVLM workshop.  
Participants do **not** need to clone this repo manually — the Colab notebook does it automatically.

---

## What's inside

```
other_resources/
├── attributes/
│   └── paddy_disease/          # Compact attribute descriptions per class
│       ├── bacterial_leaf_blight.txt
│       ├── bacterial_leaf_streak.txt
│       ├── bacterial_panicle_blight.txt
│       ├── blast.txt
│       ├── brown_spot.txt
│       ├── dead_heart.txt
│       ├── downy_mildew.txt
│       ├── hispa.txt
│       ├── normal.txt
│       └── tungro.txt
└── External_Knowledge/
    └── paddy_disease/          # Detailed disease/pest knowledge per class
        └── (same 10 .txt files)
```

---

## How to run the workshop

1. Open the notebook in Google Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rajashikdatta/paddy-vlm/blob/main/paddy_vlm_workshop.ipynb)

2. Set your **Colab Secrets** (click the 🔑 key icon in the left sidebar):

   | Secret Name | Where to get it |
   |---|---|
   | `KAGGLE_USERNAME` | [kaggle.com](https://www.kaggle.com) → Account → API |
   | `KAGGLE_KEY` | Same Kaggle API token page |
   | `HF_TOKEN` | [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens) |

3. Change runtime to **T4 GPU**: `Runtime → Change runtime type → T4 GPU`

4. Run cells **top to bottom** — no uploads, no manual steps.

---

## Dataset

The notebook automatically downloads the  
[Paddy Disease Classification Dataset](https://www.kaggle.com/competitions/paddy-disease-classification/data) from Kaggle.

---

## Classes covered (10 total)

| Class | Type |
|---|---|
| blast | Disease |
| brown_spot | Disease |
| bacterial_leaf_blight | Disease |
| bacterial_leaf_streak | Disease |
| bacterial_panicle_blight | Disease |
| dead_heart | Pest |
| downy_mildew | Disease |
| hispa | Pest |
| tungro | Disease |
| normal | Healthy |

---

## References

- [LLaVA Official Repository](https://github.com/haotian-liu/LLaVA)
- [Kaggle Dataset](https://www.kaggle.com/competitions/paddy-disease-classification/data)
- [HuggingFace](https://huggingface.co)
