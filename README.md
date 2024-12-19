# Quantitative Risk Management - Implementing RAG in LLMs to reduce Risk

Dependencies:
- Have a huggingface account with access to meta-llama/Llama-3.1-8B-Instruct: https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct - you will need this for your huggingface token
- Have access to GPU power

## Setup

1. Create a virtual environment:
    ```sh
    python -m venv .venv
    ```

2. Activate the virtual environment:
    - On Windows:
        ```sh
        .venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source .venv/bin/activate
        ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

You are now ready to run the project.

## Project goal:
This project evaluates the effectiveness of Retrieval-Augmented Generation (RAG) in improving the accuracy of LLMs using a pre-trained open-source model, Llama3.1. The study focuses on queries regarding the EU AI Act—an emerging regulatory framework introduced after the model’s data cutoff. By comparing Llama3.1 responses with and without RAG, the project aims to quantify the impact of RAG retrieval on the model’s error rates and hallucination tendencies, providing insights into the benefits and limitations of RAG integration.

## Project Files:
- [QRM_RAG_LLM_Llama3.1.ipynb](https://github.com/SebastianRosenquist/QRM_LLM_Scraper/blob/main/QRM_RAG_LLM_Llama3.1.ipynb) - The main file with LLM and RAG
- [ER_Calculations.ipynb](https://github.com/SebastianRosenquist/QRM_LLM_Scraper/blob/main/ER_Calculations.ipynb) - Calculations file with Results and Findings