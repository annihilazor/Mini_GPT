# Mini-GPT — A Transformer Language Model Built From Scratch

Mini-GPT is a fully transparent, from-scratch implementation of a GPT-style Transformer language model using **Python** and **PyTorch**.  
This project follows core architectural principles of GPT-2 (124M) and shows exactly how modern LLMs work under the hood — from tokenization to training to text generation.

---

## Features

###   **Custom Tokenizer**
- Byte Pair Encoding (BPE) implemented from scratch  
- Converts raw text into subword tokens  
- Reversible encoding/decoding pipeline  

###   **Model Architecture**
- Token embeddings + positional embeddings  
- Multi-head **causal** self-attention  
- LayerNorm, GELU, and residual connections  
- Fully implemented Transformer blocks  
- GPT-2–style architecture in PyTorch  

###   **Training Pipeline**
- Input–target data pair generation  
- Full pre-training loop coded manually  
- Cross-entropy loss for next-token prediction  
- Model evaluation on real text data  

###   **Text Generation**
- Temperature scaling  
- Top-k sampling  
- Auto-regressive next-token generation  

---



