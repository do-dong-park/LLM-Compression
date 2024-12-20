# LLM-Compression

## Overview
LLM-Compression is a project focused on compressing large language models (LLMs) to make them more efficient and faster while maintaining their performance. This repository contains various tools and techniques for model pruning, quantization, and other compression methods.

## Submodules
This project includes the following submodules:

### llm-awq
Located in [submodules/llm-awq](submodules/llm-awq/), this submodule provides tools for quantizing and optimizing LLMs. Key components include:
- [entry.py](submodules/llm-awq/awq/entry.py): Entry point for the quantization process.
- [kernels](submodules/llm-awq/awq/kernels/): Custom kernels for optimized computation.
- [quantize](submodules/llm-awq/awq/quantize/): Quantization utilities.
- [utils](submodules/llm-awq/awq/utils/): Helper functions and utilities.

### LLM-Pruner
Located in [submodules/LLM-Pruner](submodules/LLM-Pruner/), this submodule provides tools for pruning LLMs to reduce their size and improve inference speed. Key components include:
- [generate.py](submodules/LLM-Pruner/generate.py): Script for generating pruned models.
- [hf_prune.py](submodules/LLM-Pruner/hf_prune.py): Pruning script for Hugging Face models.
- [llama3.py](submodules/LLM-Pruner/llama3.py): Pruning script for LLaMA models.
- [post_training.py](submodules/LLM-Pruner/post_training.py): Post-training optimization script.
- [test_speedup.py](submodules/LLM-Pruner/test_speedup.py): Script for testing the speedup of pruned models.

### bitsandbytes
pip install bitsandbytes

## Examples
The repository includes several examples to demonstrate the usage of the tools:
- [chat_demo.ipynb](submodules/llm-awq/examples/chat_demo.ipynb): Jupyter notebook for a chat demo.
- [convert_to_hf.py](submodules/llm-awq/examples/convert_to_hf.py): Script to convert models to Hugging Face format.
- [llava_demo.ipynb](submodules/llm-awq/examples/llava_demo.ipynb): Jupyter notebook for LLAVA demo.

## License
This project is licensed under the terms of the [LICENSE](submodules/llm-awq/LICENSE) file.

## Requirements
To install the required dependencies, refer to the [requirement.txt](submodules/LLM-Pruner/requirement.txt) file.

## Getting Started
To get started with LLM-Compression, clone the repository and initialize the submodules:

