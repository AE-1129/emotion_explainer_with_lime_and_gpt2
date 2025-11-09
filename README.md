# Emotionally-and-Culturally-Aware-Chatbot-Using-LLMs

Emotion-Aware Text Analysis and Generation

This project combines emotion recognition, explainability (via LIME), and text generation into a single pipeline.
It first detects the dominant emotion in a given text using the pre-trained model
j-hartmann/emotion-english-distilroberta-base

Limitations
The text generation quality is currently limited because the base model (GPT-2) is not fine-tuned for emotional response generation.
As a result, some generated texts may appear generic, inconsistent, or unrelated to the user’s emotion.

How to Improve the Text Generation
To enhance the accuracy and emotional alignment of generated responses, consider:
Fine-tuning GPT-2 or a larger language model (e.g., GPT-Neo, T5) on a dataset of emotionally-labeled dialogues.
Incorporating emotion embeddings or sentiment scores into the model’s input.
Using reinforcement learning with human feedback (RLHF) or prompt engineering to guide the tone and empathy level.
Experimenting with temperature, top-k, and top-p parameters for more controlled generation.
