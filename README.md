# Qwen2.5-VL

Official codebase for Qwen2.5-VL, a family of advanced vision-language models.

## Overview

Qwen2.5-VL is a versatile vision-language model designed for various multimodal tasks including visual question answering, image captioning, document understanding, and more.

## Features

- State-of-the-art performance on various VL benchmarks
- Support for multiple image resolutions
- Efficient inference
- Easy-to-use API

## Installation

```bash
pip install qwen-vl
```

## Usage

```python
from qwen_vl import QwenVL

model = QwenVL.from_pretrained("Qwen/Qwen2.5-VL")
result = model.generate("What is in this image?", image_path="image.jpg")
```

## Related Projects

1. related project [DeepSeek-VL2](https://github.com/deepseek-ai/DeepSeek-VL2)
2. related project [Aria](https://github.com/rhymes-ai/Aria)
3. related project [Kimi-VL](https://github.com/MoonshotAI/Kimi-VL)

## License

This project is licensed under the Apache License 2.0.
