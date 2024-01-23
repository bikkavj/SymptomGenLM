# SymptomGenLM
## SymptomGen: Medical Symptom Description Assistant (Language Model)

SymptomGen is a DistilGPT-2 (smallest version of Generative Pre-trained Transformer 2)-powered Health Description Assistant focused on generating detailed medical symptom descriptions. 
Users input prompts directly into the notebook, leveraging the GPT-2 model to generate coherent and informative symptom descriptions. 

## GPT-2 Model Configuration:

The GPT-2 model consists of a series of transformer blocks, each containing self-attention mechanisms and feedforward neural networks. SymptomGen utilizes the pre-trained GPT-2 model from the Transformers library. The model configuration includes an embedding layer, multiple transformer blocks, and a linear layer for predicting the next token in a sequence.

## Tokenization and Input Encoding:

SymptomGen uses the GPT-2 tokenizer to convert input text into a sequence of tokens. These tokens are then encoded into tensor representations suitable for input into the GPT-2 model. The tokenization process enables the model to understand and process the input information effectively.

## Generating Symptom Descriptions:

The generate method is employed to generate symptom descriptions based on the input token sequence. The model takes into account various parameters such as max_length, do_sample, temperature, and repetition_penalty to control the generation process. The resulting output is a sequence of tokens representing the generated text.

## Decoding Output:

The generated token sequence is then decoded using the tokenizer, skipping special tokens to obtain the final coherent text output.
