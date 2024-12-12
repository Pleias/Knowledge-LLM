## Knowledge-LLM, 

**Knowledge-LLM** is a Pleias in-development library to run knowledge management projects at scale on small language models. 

In contrast with most LLM libraries, Knowledge-LLM is tightly integrated with model development. Pleias is pretraining small language models end-to-end for knowledge management tasks. This approach opens up many opportunities to bundle core features into the model design. 

All Pleias instruct models rely on special tokens to properly label the input and output data. This library will provide all the necessary intermediary steps to format existing data to the expected structure.

As a starter, Knowledge-LLM provide samples of code notebook that can be run on Google Colab:

## Retrieval Augmented-Generation
Pleias has released two models for retrieval-augmented generation:
* [Pleias-Nano](https://huggingface.co/PleIAs/Pleias-Nano), a 350 million parameters model (smaller than GPT2-medium).
* [Pleias-Pico](https://huggingface.co/PleIAs/Pleias-Pico), a 1.2 billion parameters model.

Both models are multilingual and supports advanced feature that are currently non-existent in small models of corresponding size:
* Built-in references to document.
* Grounding and detailed quotations in support to statements.
* Source analysis, similarly to a o1-style thinking step.
