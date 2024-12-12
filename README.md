## Knowledge-LLM, a software-model library for knowledge management

**Knowledge-LLM** is a Pleias in-development library to run knowledge management projects at scale on small language models. 

In contrast with most LLM libraries, Knowledge-LLM is tightly integrated with model development. Pleias is pretraining small language models end-to-end for knowledge management tasks. This approach opens up many opportunities to bundle core features into the model design. 

All Pleias instruct models rely on special tokens to properly label the input and output data. This library will provide all the necessary intermediary steps to format existing data to the expected structure.

As a starter, Knowledge-LLM provide code notebooks that can be run on Google Colab:
* [Pleias-Pico-SPQR-Multilingual](https://github.com/Pleias/Knowledge-LLM/blob/main/notebook/Pleias_Pico_SPQR_LLM_multilingual.ipynb): a multilingual RAG demo for the Pico RAG model (350m) on ancient greek and roman literature ([Use it on Colab](https://colab.research.google.com/drive/1G1LhjdzOTfk4YM5w1Rm_IRp1RoTqMdPy?usp=sharing))
* [Pleias-Nano-SPQR-Multilingual](https://github.com/Pleias/Knowledge-LLM/blob/main/notebook/Pleias_Nano_SPQR_LLM_multilingual.ipynb): a multilingual RAG demo for the Nano RAG model (1.21 billion parameters) on ancient greek and roman literature ([Use it on Colab](https://colab.research.google.com/drive/1G1LhjdzOTfk4YM5w1Rm_IRp1RoTqMdPy?usp=sharing))

## Retrieval Augmented-Generation
Pleias has released two models for retrieval-augmented generation:
* [Pleias-Pico](https://huggingface.co/PleIAs/Pleias-Pico), a 350 million parameters model (smaller than GPT2-medium).
* [Pleias-Nano](https://huggingface.co/PleIAs/Pleias-Nano), a 1.2 billion parameters model.

Both models are fully multilingual with fluency in the main European languages. They support advanced feature that are currently non-existent in small models of corresponding size:
* Built-in references to document.
* Grounding and detailed quotations in support to statements.
* Source analysis, similarly to a o1-style thinking step.
