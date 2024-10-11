# Distiller

WIP

AIM: Distill LLMs into document understanding specific tasks using smaller models

What you define:
1. Task
    a. Examples - OCR, key information extraction
2. Dataset
    a. Training data you want to use
    b. Evaluation data you want benchmark
3. Task specific model architecture
    a. Donut/LayoutLMv3 for key information extraction
    b. parseq for OCR
    
You get:
1. Smaller model weights that are as good

How do you create the training data?
1. Weak labelling via LLMs
2. Manual inspection + corrections after looking at disagreements