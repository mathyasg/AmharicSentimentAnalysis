# Amharic Sentiment Analysis with Prompt Tuning

Low-resource binary sentiment classification for Amharic tweets using data augmentation and PEFT (Prompt Tuning).

## Current Status (Initial Version)
- Macro F1: ~0.70–0.75 (after basic augmentation)
- Trainable parameters: ~0.03%
- Techniques: random word swap augmentation + prompt tuning

## Planned Improvements
- Class weighting
- Back-translation augmentation (NLLB)
- Switch to LoRA
- Better hyperparameter tuning
- Gradio demo

## How to run
1. Open in Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mathyasg/AmharicSentimentAnalysis/blob/main/amharic_sentiment_peft_initial.ipynb)
2. Change runtime to T4 GPU
3. Run all cells
