---
language:
- en
library_name: transformers
tags:
- code
metrics:
- character
---

# Model Card for Model ID

<!-- Provide a quick summary of what the model is/does. -->

## Llama 2
Llama 2 is a collection of pretrained and fine-tuned generative text models ranging in scale from 7 billion to 70 billion parameters. This is the repository for the 7B pretrained model, converted for the Hugging Face Transformers format.

## Model Details
Note: Use of this model is governed by the Meta license. In order to download the model weights and tokenizer, please visit the website and accept our License before requesting access here.

Meta developed and publicly released the Llama 2 family of large language models (LLMs), a collection of pretrained and fine-tuned generative text models ranging in scale from 7 billion to 70 billion parameters. Our fine-tuned LLMs, called Llama-2-Chat, are optimized for dialogue use cases. Llama-2-Chat models outperform open-source chat models on most benchmarks we tested, and in our human evaluations for helpfulness and safety, are on par with some popular closed-source models like ChatGPT and PaLM.

### Model Description

<!-- Provide a longer summary of what this model is. -->
## Model Developers : Meta

## Variations
Llama 2 comes in a range of parameter sizes — 7B, 13B, and 70B — as well as pretrained and fine-tuned variations.

## Input Models: input text only.

## Output Models: generate text only.

## Model Architecture 
Llama 2 is an auto-regressive language model that uses an optimized transformer architecture. The tuned versions use supervised fine-tuning (SFT) and reinforcement learning with human feedback (RLHF) to align to human preferences for helpfulness and safety.

This is the model card of a 🤗 transformers model that has been pushed on the Hub. This model card has been automatically generated.


### Model Sources [optional]

Llama 2 family of models. Token counts refer to pretraining data only. All models are trained with a global batch-size of 4M tokens. Bigger models - 70B -- use Grouped-Query Attention (GQA) for improved inference scalability.

## Model Dates 
Llama 2 was trained between January 2023 and July 2023.

Status This is a static model trained on an offline dataset. Future versions of the tuned models will be released as we improve model safety with community feedback.

## License 
A custom commercial license is available at: https://ai.meta.com/resources/models-and-libraries/llama-downloads/

## Research Paper:
"Llama-2: Open Foundation and Fine-tuned Chat Models"

## Intended Use
Intended Use Cases 
Llama 2 is intended for commercial and research use in English. Tuned models are intended for assistant-like chat, whereas pretrained models can be adapted for a variety of natural language generation tasks.

To get the expected features and performance for the chat versions, a specific formatting needs to be followed, including the INST and <<SYS>> tags, BOS and EOS tokens, and the whitespaces and breaklines in between (we recommend calling strip() on inputs to avoid double-spaces). See our reference code in github for details: chat_completion.

## Out-of-scope Uses 
Use in any manner that violates applicable laws or regulations (including trade compliance laws).Use in languages other than English. Use in any other way that is prohibited by the Acceptable Use Policy and Licensing Agreement for Llama 2.

## Hardware and Software
Training Factors We used custom training libraries, Meta's Research Super Cluster, and production clusters for pretraining. Fine-tuning, annotation, and evaluation were also performed on third-party cloud compute.

[More Information Needed]

## Model Card Contact

[More Information Needed]