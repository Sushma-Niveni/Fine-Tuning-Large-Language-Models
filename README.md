# Fine-Tuning-Large-Language-Models


This project focuses on fine-tuning a large language model (LLM) using various datasets and techniques. The objective is to customize the model for specific tasks and evaluate its performance, leveraging the capabilities of advanced AI technologies.

## Preliminary Requirements

1. **HuggingFace Account**
   - Create a free account: [HuggingFace](https://huggingface.co/)

2. **Llama2 Access**
   - Request access for Llama2: [Llama2 Download](https://llama.meta.com/llama-downloads/)
   - Request access on HuggingFace: [Llama-2-7b-hf](https://huggingface.co/meta-llama/Llama-2-7b-hf)

3. **HuggingFace Token**
   - Obtain your token from: Profile -> Settings -> Access Tokens

4. **Public SSH Key**
   - Generate your SSH key: [SSH Key Setup](https://vast.ai/docs/instance-setup/ssh)
   - Send your SSH key to the project coordinator as instructed.


## Data

1. **Available Datasets**
   - **StackOverflow Dataset:** [Link](https://huggingface.co/datasets/jbrophy123/stackoverflow_dataset)
   - **Quora Dataset:** [Link](https://huggingface.co/datasets/jbrophy123/quora_dataset)
   - **Alpaca Dataset:** [Link](https://huggingface.co/datasets/jbrophy123/alpaca_dataset)
   - **Medical Dataset:** [Link](https://huggingface.co/datasets/jbrophy123/medical_dataset)
   - **Sentiment Classification Dataset:** [Link](https://huggingface.co/datasets/jbrophy123/imdb_sentiment_analysis)


2. **Training Limit**
   - Limit of 2,000 training observations.

## Model

1. **Available Models**
   - **Llama 2 7B**
   - **Mistral 7B**

2. **Model Types**
   - **Chat Versions:** Instruction fine-tuned
   - **Regular Versions:** Standard fine-tuning

3. **Model Requirement**
   - Models must have ≤7 billion parameters.
   - Models must be available on HuggingFace.

## Questions

1. **Model and Data Decisions**
   - **Data Source:** Describe the chosen dataset and the rationale behind it.
   - **Problem Addressed:** What problem does your fine-tuned model aim to solve?

2. **Concept Explanations**
   - **LoRA:** Define LoRA and its necessity.
   - **QLoRA:** Define QLoRA and its necessity.
   - **Instruction Fine-Tuning:** Explain instruction fine-tuning and how it differs from unsupervised pre-training.
   - **Approach:** Is your work considered instruction fine-tuning or unsupervised pre-training? Explain why.

3. **Coding**
   - **Commenting:** Add comments to each line of the provided code.
   - **Script Arguments:** Explain the metadata fields in the script arguments.
   - **Instance Reservation:** Complete commenting and explanations before reserving the instance.

4. **Fine-Tuning**
   - **Execution:** Fine-tune your model using the provided script or command line on Vast.ai.
   - **Save Directory:** Specify `lora_dir` to save your work. Use your HuggingFace account for storage.
   - **Model Directory:** Provide the name and directory of your model.

## Vast.ai Tutorial

1. **Generate SSH Key**
   - Create your public SSH key: [SSH Key Setup](https://vast.ai/docs/instance-setup/ssh)

2. **Instance Connection**
   - SSH Command: `ssh -p <port> root@<ip_address>`

3. **Code Transfer**
   - Use `scp` to transfer code to your Vast.ai instance.
   - Example command: `scp -r -P 40473 /local/path root@100.34.98.40:/remote/directory/`

4. **Running Code**
   - Execute code via command line or interface after logging in.
