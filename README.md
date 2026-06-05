# Online Feedback Distillation

This repository contains a research prototype for teaching lightweight language models to mimic expert feedback in reasoning tasks.

The project builds on CLEAR (Contrasting Textual Feedback with Experts and Amateurs for Reasoning), a framework where a base model generates an answer, expert and amateur models critique it, and the answer is revised using unified feedback.

Our extension replaces the fixed amateur model with an adaptive student model trained through online knowledge distillation, reducing reliance on expensive expert feedback while preserving feedback quality.

