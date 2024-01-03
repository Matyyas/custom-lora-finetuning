# custom-lora-finetuning
A custom implementation of LoRA fine-tuning strategy for a Tensorflow model from HuggingFace on sentiment analysis task (imbd dataset). This custom implementation reduced the amount of trainable parameters from 67M to 1M — a 98.5% reduction of the total trainable weights — while maintaining the same performance as a classic fine-tuning.

NB: The same logic can be extended to any Tensorflow LLMs by finding the proper linear's layers names to use in the DISTILBERT_LINEAR_MODULES_DICT (which obvisouly works for the DistilBERT model used in the example)
