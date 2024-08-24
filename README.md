# Liger Vs Unsloth Inference battle

This repository contains Jupyter Notebooks for evaluating different language models. The notebooks focus on performance metrics such as throughput and memory usage during inference. Run on Google Colab L4

## Notebooks

### 1. Evaluate Liger
This notebook evaluates the performance of the Liger model, focusing on:

- **Throughput**: Measures the number of tokens processed per second.
- **Memory Usage**: Tracks the peak GPU memory usage during inference.
- #### Preliminary Results
Gemma-2-2B
- **Throughput (tokens per second)**: 17.88
- **Peak memory  (MB)**: 10920.00

Gemma-2-9B
- **OOM**
  
Gemma-2-27B
- **OOM**

### 2. Evaluate Unsloth
This notebook evaluates the performance of the Unsloth model, focusing on:

- **Throughput**: Measures the number of tokens processed per second.
- **Memory Usage**: Tracks the peak GPU memory usage during inference.
  
#### Preliminary Results
Gemma-2-2B
- **Throughput (tokens per second)**: 19.50
- **Peak memory  (MB)**: 3144.00

Gemma-2-9B
- **Throughput (tokens per second)**: 10.00
- **Peak memory (MB)**: 7328.00

Gemma-2-27B
- **Throughput (tokens per second)**: 8.08
- **Peak memory reserved (MB)**: 16328.00
