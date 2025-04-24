# TryOnAfrica
Virtual try-on app focused on African textiles (Ankara, Kente, etc.) built on TryOnDiffusion.
TryOnAfrica/
│
├── README.md                  # Overview of the project
├── requirements.txt           # Dependencies
├── app/                       # Main app files
│   ├── main.py                # Entry point
│   ├── ui/                    # UI components (streamlit or gradio)
│   ├── core/                  # Core logic, model loading, inference
│   └── assets/                # Sample Ankara/Kente images
│
├── models/                    # Model checkpoints or references
│   └── tryondiffusion/        # Forked or adapted TryOnDiffusion code
│
├── utils/                     # Helper functions
│
└── notebooks/                 # Any demo or training notebooks

# README.md

# TryOnAfrica

**TryOnAfrica** is a virtual try-on web app tailored to showcase African fashion, including styles like Ankara and Kente. It enables users to try garments on images of themselves using cutting-edge AI models based on TryOnDiffusion.

## 🌍 Key Features
- Upload a photo and try on various African textile styles
- Built on TryOnDiffusion + Stable Diffusion
- Clean, intuitive UI (Streamlit or Gradio)

## 🔧 Tech Stack
- Python
- Streamlit or Gradio
- Stable Diffusion & TryOnDiffusion

## 🚀 Getting Started
```bash
pip install -r requirements.txt
python app/main.py
```

## 📦 Folder Structure
- `app/`: UI, logic, and assets
- `models/`: Model code and checkpoints
- `utils/`: Helpers and utilities
- `notebooks/`: Experiments, demos

## 🤝 Contributing
We welcome community involvement! Submit issues, improvements, or new styles!

## 📄 License
Open source under MIT License.
