# Kokoro-82M ONNX Runtime Inference

![Downloads](https://img.shields.io/github/downloads/yakhyo/kokoro-82m-onnx/total)
[![GitHub Repo stars](https://img.shields.io/github/stars/yakhyo/kokoro-82m-onnx)](https://github.com/yakhyo/kokoro-82m-onnx/stargazers)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/yakhyo/kokoro-82m-onnx)

This repository contains minimal code and resources for inference using the **Kokoro-82M** model. The repository supports inference using **ONNX Runtime**.

<table>
  <tr>
    <td>Machine learning models rely on large datasets and complex algorithms to identify patterns and make predictions.</td>
    <td>Did you know that honey never spoils? Archaeologists have found pots of honey in ancient Egyptian tombs that are over 3,000 years old and still edible!</td>
  </tr>
  <tr>
    <td align="center">
       <video controls autoplay loop src="https://github.com/user-attachments/assets/a8e9bfb7-777a-4b44-901c-c79c39c02c6f" ></video>
    </td>
    <td align="center">
      <video controls autoplay loop src="https://github.com/user-attachments/assets/358723ad-c0ab-44a3-90cc-64d89c042c9a" ></video>
    </td>
  </tr>
</table>

## Features

- **ONNX Runtime Inference**: Kokoro-82M (v0_19) Minimal ONNX Runtime Inference code. It supports `en-us` and `en-gb`.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yakhyo/kokoro-82m.git
   cd kokoro-82m
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Install `espeak` for text-to-speech functionality:
   Linux:
   ```bash
   apt-get install espeak -y
   ```

---

## Usage

### Download ONNX Model

[click to download](https://github.com/yakhyo/kokoro-82m/releases/download/v0.0.1/kokoro-v0_19.onnx)

### Jupyter Notebook Inference Example

Run inference using the jupyter notebook:

[example.ipynb](example.ipynb)

### CLI Inference

Specify input text and model weights in `inference.py` then run:

```bash
python inference.py
```

---

## License

This project is licensed under the [MIT License](LICENSE).
Model weights licensed under the [Apache 2.0](#license)

---

## Acknowledgments

- https://huggingface.co/hexgrad/Kokoro-82M
