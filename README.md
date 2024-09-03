# Basic Applications of Large-Language Models

## Tutorial for [Design++](https://designplusplus.ethz.ch) [Summer School AI in AEC 2024](https://designplusplus.ethz.ch/education/summer-school.html), ETH Zurich

Open the tutorial notebook [here](intro_to_llms.ipynb)
 
## Setup Environment

First create a python 3 environment. If you use conda then in the terminal run:

    conda create -n llm_tutorial python=3 ipykernel pandas numpy

Activate the environment:

    conda activate llm_tutorial

Install the needed packages:

    pip install langchain langchain-openai langchain-community langchain-text-splitters tiktoken rich beautifulsoup4 pypdf