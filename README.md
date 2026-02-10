# NLP Berto Class

NLP and deep learning toolkit covering text classification with BERT, Named Entity Recognition, GANs, and image processing.

## Overview

A collection of ML/DL experiments and tools built with PyTorch and TensorFlow, focusing on transformer-based NLP tasks and generative models.

## Modules

| Module | Description |
|--------|-------------|
| `text_class/` | Text classification using BERT/Transformers |
| `text_ner/` | Named Entity Recognition |
| `gan/` | Generative Adversarial Network experiments |
| `image/` | Image processing utilities |

## Project Structure

```
├── text_class/          # BERT text classification
│   ├── preprocess/      # Data preprocessing
│   ├── run_class.py     # Training/inference entry point
│   └── README.md        # Dataset format documentation
├── text_ner/            # Named Entity Recognition
├── gan/                 # GAN experiments (DCGAN)
├── image/               # Image processing
├── ClassFile.py         # Shared file/data utilities
└── requirements.txt
```

## Tech Stack

- **Language:** Python 3.6–3.8
- **ML Frameworks:** PyTorch 1.7+, TensorFlow 2.4+
- **NLP:** Hugging Face Transformers
- **GPU:** CUDA 11.0, cuDNN 8.0

## Requirements

- Python 3.6+
- CUDA 11.0 compatible GPU (recommended)

## Installation

```bash
pip install -r requirements.txt
```

For GPU support (PyTorch + CUDA 11):
```bash
pip install torch==1.7.1+cu110 torchvision==0.8.2+cu110 -f https://download.pytorch.org/whl/torch_stable.html
```

## Usage

### Text Classification
Prepare your dataset (tab-separated text + label per line), then:
```bash
cd text_class
python run_class.py --data_dir /path/to/dataset
```

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

## Author

**Jose** — [@aifriend](https://github.com/aifriend)
