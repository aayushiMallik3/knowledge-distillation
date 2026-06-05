# Online Feedback Distillation

## Problem

CLEAR uses expert and amateur feedback to iteratively improve reasoning outputs.

However, the amateur model is static and often produces noisy feedback.

## Our Contribution

We replace the fixed amateur model with an adaptive student model trained online through knowledge distillation.

## Architecture

Prompt
→ Initial Answer
→ Expert Feedback
→ Student Feedback
→ Knowledge Distillation
→ Unified Feedback
→ Revision
→ Self-Critique
→ Final Answer

## Models

Teacher:
Llama 3.1 8B

Student:
TinyLlama 1.1B

## Datasets

GSM8K
Alpaca
DROP

## Metrics

BERTScore
ROUGE-L
BLEU
Cosine Similarity
Detoxify
