# 🖼️ Visual Art using Stable Diffusion Image Generator (Dreamlike Photoreal 2.0)

This project uses **Hugging Face Diffusers** and **Stable Diffusion** to generate high-resolution (768×768) images with GPU acceleration.  
The script loads the **Dreamlike Photoreal 2.0** model, supports optional schedulers, enables xFormers memory optimization, and generates multiple images from a text prompt.

---

## 🚀 Features

- Generate **photorealistic 768×768 images**
- Use any Stable Diffusion model from Hugging Face Hub
- Optional scheduler customization (PNDM, DDIM, LMS, Euler, DPM Solver)
- Memory-efficient GPU execution using **xFormers**
- Supports **negative prompts** for content filtering
- Reproducible results using a random seed
- Save output images automatically

---

## 📦 Installation

Run the following commands inside your Jupyter Notebook:

```python
%pip install --quiet --upgrade diffusers transformers accelerate mediapy triton scipy ftfy spacy==3.4.4
%pip install -q xformers==0.0.16rc425

