# 🎨 Image Generation using Stable Diffusion and Comfy UI

This project showcases an image generation pipeline using **Stable Diffusion** through the **ComfyUI** interface. The setup provides a powerful, modular environment for creating high-quality AI-generated images using a node-based workflow.

---

## 🧠 Overview

**ComfyUI** is a powerful and flexible GUI for Stable Diffusion, ideal for building custom workflows without needing to write code. This project demonstrates how to:

- Generate images from text prompts
- Customize workflows via nodes
- Load custom models and LoRAs
- Export results efficiently

---

## 🚀 Features

- 🖼️ **Text-to-Image Generation**
- 🛠️ **Customizable Workflows** via drag-and-drop node editing
- 🧩 **Model Flexibility** – Easily switch between SD 1.5, SDXL, custom checkpoints, etc.
- 🖌️ **Support for Inpainting, Upscaling, and Post-Processing**
- 📁 Organized output folder structure

---

## 🧰 Requirements

- [Python 3.10+](https://www.python.org/downloads/)
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- CUDA-compatible GPU (recommended for performance)
- Stable Diffusion model(s)

---

## 🛠️ Installation

1. **Clone ComfyUI**:
   ```bash
   git clone https://github.com/comfyanonymous/ComfyUI.git
   cd ComfyUI
2. **Download and Place Models**:
    > Place your Stable Diffusion models in:
    ```bash
    ComfyUI/models/checkpoints/
3. **Run the App**:
   ```bash
   python main.py
4. **Open your browser and go to**:
   ```cpp
   http://127.0.0.1:8188

---

## 📁 Project Structure

| Folder/File        | Description                                |
|--------------------|--------------------------------------------|
| `README.md`        | Project overview                           |
| `outputs/`         | Folder containing generated images         |
| `models/`          | Stable Diffusion models and LoRAs          |
| `workflows/`       | ComfyUI workflow files (.json)             |

---

## 📥 Model Download

Due to GitHub file size limits, large model files are hosted externally.

➡️ Download models from Google Drive [https://drive.google.com/drive/folders/1aC_51w_0GxT96Fqz-o187RaBTaLYIftv?usp=drive_link]

Place them in models/checkpoints/ after downloading.

---

## 🖼️ Example Results

Here are a few sample generations from the project:
| Prompt	                                               |       Output |
|-------------------------------------------------------|--------------|
|“A futuristic city at night, ultra-realistic, neon”	  |              |

---

## 📜 License

This project is for educational and non-commercial use. Respect the licenses of the models you use (e.g., Stability AI, Hugging Face, etc.).

---

## 🙌 Acknowledgements
   - ComfyUI
   - Stable Diffusion by Stability AI
   - Community contributions on Civitai, Hugging Face, etc.

---

## 📬 Contact

For any questions or collaborations, feel free to reach out!
```yaml
Want me to help you generate example workflow images, screenshots, or fill in your actual model links? Just let me know!
