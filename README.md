# Haiku_Generator

A fine-tuned GPT-2 model trained to generate structured and poetic haikus based on the 5/7/5 syllable form. This project uses the davanstrien/haiku_dpo dataset and compares training using various learning rate schedulers.


# DATASET

Source: Hugging Face - davanstrien/haiku_dpo

Structure: used the chosen column only (high-quality human-preferred haikus)

# MODEL

Base Model: gpt2-medium

Training Tool: Hugging Face Transformers + Datasets + Trainer

Tokenizer: GPT2Tokenizer with <EOS> mapped to pad_token

Max Token Length: 64 tokens per haiku

Subset: Trained on ~4,500 high-quality haikus

# SAMPLE HAIKU
Haiku 1 
Whispering leaves dance,
Nature's symphony in tune,
Spring's gentle heart.

Haiku 2 
Amber sun ascends,
Stillness embraces the universe,
Stillness in her embrace.
