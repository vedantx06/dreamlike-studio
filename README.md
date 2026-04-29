# 🎨 Text-to-Image Generator using Stable Diffusion

## 📌 Description

This project is a Text-to-Image Generation system that creates images from text prompts using Stable Diffusion.

---

## 🚀 Features

* Generate images from text
* Uses Stable Diffusion model
* Easy prompt-based usage
* Runs on Google Colab with GPU

---

## 🛠️ Tech Stack

* Python
* PyTorch
* Hugging Face Diffusers
* Google Colab

---

## ⚙️ How to Run

1. Open the notebook in Google Colab
2. Enable GPU (Runtime → Change runtime → GPU)
3. Run all cells

---

## ✍️ Usage

Example prompt:

```python
prompt = "A futuristic city with neon lights"
image = pipe(prompt).images[0]
image.save("output.png")
```

---

## 📂 Output

Generated image will be saved as:

```
output.png
```

---

## 📜 License

MIT License
