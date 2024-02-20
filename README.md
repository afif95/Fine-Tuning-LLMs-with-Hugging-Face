# Fine-Tuning LLMs with Hugging Face
This repository contains code for fine-tuning large language models (LLMs) using the Hugging Face Transformers library.

## Features:
- Supervised Fine-Tuning of LLMs with peft for parameter efficiency.
- 4-bit quantization using nf4 data type for reduced model size and faster inference.
- Causal language modeling tasks.
- LORA regularization for overfitting prevention.
- Easy usage with pre-defined training arguments and data loading.

## Requirements:
- The source dataset: https://huggingface.co/datasets/gamino/wiki_medical_terms
- The formatted dataset: https://huggingface.co/datasets/aboonaji/wiki_medical_terms_llam2_format
- The pre-trained Llama 2 model: https://huggingface.co/aboonaji/llama2finetune-v2
- The from_pretrained method from the AutoModelForCausalLM class: https://huggingface.co/docs/transformers/model_doc/auto#transformers.AutoModelForCausalLM.from_pretrained
- The BitsAndBytesConfig class from the transformers library: https://huggingface.co/docs/transformers/main_classes/quantization#transformers.BitsAndBytesConfig
- The from_pretrained method from the AutoTokenizer class: https://huggingface.co/docs/transformers/model_doc/auto#transformers.AutoTokenizer.from_pretrained
- The TrainingArguments class from the transformers library: https://huggingface.co/docs/transformers/main_classes/trainer#transformers.TrainingArguments
- The SFTTrainer class from the trl library: https://huggingface.co/docs/trl/sft_trainer#trl.SFTTrainer
- The LoraConfig class from the peft library: https://huggingface.co/docs/peft/v0.7.1/en/package_reference/lora#peft.LoraConfig
- The pipeline function from the transformers library: https://huggingface.co/docs/transformers/main/en/quicktour#pipeline

## Outputs

![1](https://github.com/afif95/Fine-Tuning-LLMs-with-Hugging-Face/assets/34897455/f9a8e2e3-bc23-4098-b5c6-050a1eefa578)
![2](https://github.com/afif95/Fine-Tuning-LLMs-with-Hugging-Face/assets/34897455/55205146-b278-4cd9-a1c7-73611a80552f)
![3](https://github.com/afif95/Fine-Tuning-LLMs-with-Hugging-Face/assets/34897455/899f15c8-f68a-41d7-9424-ed1e96a4da40)
![4](https://github.com/afif95/Fine-Tuning-LLMs-with-Hugging-Face/assets/34897455/f6aead52-351f-456c-81d4-109f8db66466)
![5](https://github.com/afif95/Fine-Tuning-LLMs-with-Hugging-Face/assets/34897455/630d63fb-a2ce-465b-b42d-5bb7b4dc3867)
