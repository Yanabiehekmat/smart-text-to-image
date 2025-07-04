# 🖼️ Smart Text-to-Image Generator  
**Advanced Vision School — Project 3**  

This project implements an intelligent application for generating images from text prompts using Stable Diffusion models. The app provides an interactive and user-friendly interface via Gradio, allowing users to easily enter a prompt and see the generated image.  

## 🚀 Features  
- **Model selection:** Users can choose between two models: `SD15 (Stable Diffusion v1-5)` or `SDXL (Stable Diffusion XL)`.  
- **CFG scale control:** Users can adjust the classifier-free guidance (CFG) scale for creativity and prompt adherence.  
- **Image size selection:** Options to select image dimensions (`512x512`, `768x512`, `768x768`).  
- **Random seed input:** Allows reproducibility or random variations.  
- **Automatic execution:** The app runs fully without requiring code modifications.  
- **Gradio interface with public shareable link**  

## 💻 Technologies Used  
- [Diffusers](https://huggingface.co/docs/diffusers/index)  
- [Transformers](https://huggingface.co/docs/transformers/index)  
- [Gradio](https://gradio.app)  
- Google Colab (with GPU acceleration)  

## 📊 Example Outputs  

| Prompt | Model | CFG | Size | Example |
|---------|--------|------|-------|---------|
| *A futuristic cityscape at sunset* | SDXL | 7.5 | 768x512 | ![example](https://via.placeholder.com/400x200?text=Generated+Image) |

*(Replace the placeholder above with your generated image link or screenshot if needed.)*

## ⚙️ How to Run  

1️⃣ Clone the repository:  
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
````

2️⃣ Open the code in Google Colab (recommended for GPU):

* Upload `main.py` or copy the code into a Colab notebook cell
* Set runtime to **GPU**
* Run all cells

3️⃣ Use the Gradio link shown in the output to access the app.

## 📌 Notes

* All models are loaded from public Hugging Face repositories.
* The app disables the default safety checker; it is intended for educational use only.
* The generated Gradio link is temporary. For permanent deployment, you may use Hugging Face Spaces.

## 📎 Repository Link

👉 [GitHub Repository](https://github.com/your-username/your-repo-name)

## ✨ Author

This project was developed as part of the Advanced Vision School coursework.
