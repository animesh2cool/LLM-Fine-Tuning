# LLM Fine-Tuning Workflows (Qwen 3)

This repository contains workflows for fine-tuning Large Language Models (LLMs), specifically optimized for the **Qwen 3** architecture.

It provides two distinct pipelines designed for different hardware constraints:
1.  **Standard LoRA:** High-performance, 16-bit precision training for high-end GPUs (A100, H100).
2.  **QLoRA (4-bit):** Memory-efficient quantization for consumer GPUs (T4, RTX 3060/4090).

## 📋 Prerequisites

Before running either notebook, ensure you have the necessary dependencies installed.

```bash
pip install -q transformers datasets peft torch accelerate bitsandbytes
