### NLP Assignment 7 
# In this assignment, I explored and compared different fine-tuning strategies for BERT-based models on a toxic comment classification task. Specifically, I implemented:

# Odd Layer Distillation: Using layers {1, 3, 5, 7, 9, 11} from the teacher model.

# Even Layer Distillation: Using layers {2, 4, 6, 8, 10, 12}.

# LoRA (Low-Rank Adaptation): A parameter-efficient approach that adds trainable low-rank matrices to the full 12-layer BERT.

# After training and evaluating all three models, I analyzed their performance in terms of training loss and test accuracy. I found that LoRA provided a more memory-efficient training process, while the distilled models (Odd/Even) showed competitive results depending on the layer selection.

# Additionally, I developed a simple web application that allows users to input text and receive toxicity predictions in real time.

# This project provided hands-on experience with knowledge distillation, parameter-efficient tuning, and deploying NLP models — all essential techniques for modern-day NLP applications.
