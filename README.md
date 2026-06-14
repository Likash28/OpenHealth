# OpenHealth — AI-Powered Healthcare Platform

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

An AI-powered healthcare platform for multi-disease detection across brain, kidney, heart, liver, and lungs. Uses deep learning (VGG-19, ResNet50), traditional ML (XGBoost, Random Forest), and open-source LLMs from Hugging Face and Google Generative AI for personalized health insights.

> **Disclaimer:** This tool is for educational and research purposes only. It is not a substitute for professional medical advice.

## Features

- Multi-organ disease detection — brain MRI, chest X-ray, kidney, liver, heart
- Deep learning models: VGG-19, ResNet50, DeepLab segmentation
- ML models: XGBoost, Random Forest for tabular health data
- LLM-powered health insights via Hugging Face + Google Generative AI
- AI dietitian with food and lifestyle recommendations
- MLOps ready — Docker, DVC, MLflow support

## Tech Stack

| Category | Tools |
|----------|-------|
| Deep Learning | TensorFlow, Keras, PyTorch |
| ML | XGBoost, Random Forest, Scikit-learn |
| LLMs | HuggingFace Transformers, Google Generative AI |
| MLOps | Docker, DVC, MLflow |
| Backend | Python, FastAPI |

## Getting Started

```bash
git clone https://github.com/Likash28/OpenHealth.git
cd OpenHealth
pip install -r requirements.txt
python app.py
```

## Project Structure

```
├── app.py              # Main application entry
├── models/             # Trained model files
├── static/             # Frontend assets
├── templates/          # HTML templates
├── requirements.txt
└── Dockerfile
```

## Contributing

Pull requests are welcome. Open an issue first for major changes.

## License

[MIT](LICENSE)
