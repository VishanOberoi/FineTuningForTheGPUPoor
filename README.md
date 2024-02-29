# Fine Tuning For The GPU Poor: A Guide to Optimizing Language Models

Welcome to FineTuningForTheGPUPoor, a comprehensive guide designed to empower you with the knowledge to fine-tune open-source large language models (LLMs) using the free T4 GPU available on Colab. This project is a testament to the ingenuity in the AI community, demonstrating that resource constraints should not be a barrier to innovation.

<p align='center'>
  <img src='https://venturebeat.com/wp-content/uploads/2023/07/nuneybits_vector_art_of_a_llama_programming_8c825672-172b-4e69-a6f1-b7c9e8bf5294.png?w=1200&strip=all'>
</p>

## Introduction

This project is for anyone interested in optimizing language models without the need for expensive GPU resources. You'll learn how to effectively fine-tune models to achieve high-quality output suitable for conversational AI applications.

## Prerequisites

To get started, you will need the following:
- Hugging Face Account with Authentication Token
- Permission to access the Llama Model (a gated model). Fill the form [here](https://llama.meta.com/llama-downloads/)
(You should get a mail within about half an hour)
- A dataset for your model to learn from (or you can create one - process mentioned [here](Data_Prep.ipynb)
- Ngrok Account with Authentication Token (if you want to see a frontend)

## Technologies Used

- **PEFT (Prompt-tuning with Efficient Fine-tuning):** A technique for fine-tuning language models in a parameter-efficient way.
- **LoRA (Low-Rank Adaptation):** A method to adapt large language models with minimal changes.
- **QLoRA (Quantized LoRA):** A quantized version of LoRA for efficient performance.
- **Chainlit:** A framework to build web-based interfaces for Python applications.
- **Gradio:** A library to create customizable UI components for machine learning models.
- **Langchain:** A toolkit for integrating conversational memory into language models.
- **Hugging Face:** A platform for the AI community to build, train, and deploy ML models.
- **GGUF (Generic GPU Utility Format):** A format for quantized model adaptation.
- **Ngrok:** A service that provides real, functional URLs to locally hosted applications.


## Features

- **Dataset Creation:** Instructions on how to create a dataset for your model to learn from.
- **Model Fine-tuning:** Step-by-step guidance on fine-tuning language models using QLoRA and PEFT.
- **Conversational AI:** Techniques for integrating conversational memory into your models.
- **Deployment:** Methods to deploy your model with a front-end interface using Gradio or Chainlit and Ngrok.

## Model Availability

The fine-tuned models are available on [Hugging Face](https://huggingface.co/vishanoberoi/Llama-2-7b-chat-hf-finedtuned-to-GGUF).

## Model Card

Our fine-tuned model, `vishanoberoi/Llama-2-7b-chat-hf-finedtuned-to-GGUF`, is optimized for conversational AI, providing high-quality, contextually relevant responses for company-specific data. Check the model, and the code to run it directly [here]().

### Developed by:
Vishan Oberoi and Dev Chandan

### License:
MIT

### Base Model:
[LLaMA](https://huggingface.co/meta-llama/Llama-2-7b-chat-hf)

### Further Reading:
- [LLaMA Paper](https://arxiv.org/abs/2302.13971)
- [QLORA Paper](https://arxiv.org/abs/2305.14314)
- [llama.cpp Documentation](https://github.com/ggerganov/llama.cpp)
- [Chainlit Documentation](https://docs.chainlit.io/get-started/overview)
- [Langchain Documentation](https://python.langchain.com/docs/get_started/introduction)


## Conclusion

By the end of this project, you'll have the skills to fine-tune any language model, create a dataset, integrate conversational capabilities, and deploy your model with an interactive front-end. We're excited to see the solutions you develop with these tools and techniques.

---

*For a deeper dive into the code and step-by-step instructions, refer to the notebooks included in the GitHub repository and the comprehensive master notebook that serves as a pipeline for the entire process.*
