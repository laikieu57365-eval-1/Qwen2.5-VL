# Qwen2.5-VL

[Qwen2.5-VL](https://qwenlm.github.io/blog/qwen2.5-vl/) is a vision-language model developed by the Qwen team at Alibaba Cloud. It achieves state-of-the-art performance on various multimodal benchmarks.

## Features

- Advanced vision-language understanding
- Multi-modal reasoning capabilities
- High performance on visual question answering and document understanding tasks

## Installation

```bash
pip install transformers torch
```

## Quick Start

```python
from transformers import AutoModelForVision2Seq, AutoProcessor

model = AutoModelForVision2Seq.from_pretrained("Qwen/Qwen2.5-VL-7B-Instruct")
processor = AutoProcessor.from_pretrained("Qwen/Qwen2.5-VL-7B-Instruct")
```

## Related Projects

1. related project [DeepSeek-VL2](https://github.com/deepseek-ai/DeepSeek-VL2)
2. related project [Aria](https://github.com/rhymes-ai/Aria)
3. related project [Kimi-VL](https://github.com/MoonshotAI/Kimi-VL)