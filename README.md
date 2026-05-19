# 🎨 Gradio Stable Diffusion V1.5 Test (`2_gradio_Stable_Diffusion_V1_5_Test.ipynb`)

A simple interactive web interface built with **Gradio** to test and generate AI images using the **Stable Diffusion V1.5** model. This project runs entirely inside a Jupyter Notebook, making it easy to experiment with text-to-image generation.

---

## 🚀 Features

* **Text-to-Image Generation:** Create high-quality images simply by typing text prompts.
* **Gradio Web UI:** A user-friendly, interactive web browser interface running directly from the notebook.
* **Parameter Tuning:** Adjust parameters like inference steps, guidance scale (CFG), and image dimensions on the fly.
* **Public/Local Link:** Generates a local URL (and an optional shareable public link) to interact with the model.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python
* **Core AI Model:** Stable Diffusion V1.5 (`runwayml/stable-diffusion-v1-5`)
* **Libraries:** * `diffusers` (Hugging Face)
    * `transformers`
    * `gradio` (For the Web UI interface)
    * `torch` (PyTorch with CUDA support recommended)

---

## 🏃 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/tommysanjaya/your-repo-name.git](https://github.com/tommysanjaya/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Install the required packages:**
    ```bash
    pip install torch torchvision diffusers transformers gradio acceleration
    ```

3.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook 2_gradio_Stable_Diffusion_V1_5_Test.ipynb
    ```

4.  **Run all cells.** Once the Gradio interface launches, click the local URL (e.g., `http://127.0.0.1:7860`) generated in the output to open the Web UI.

---

## 📊 Sample UI Layout

When you run the notebook, Gradio will generate an interface that looks like this:
* **Input Box:** Enter your prompt (e.g., *"A futuristic city in the style of cyberpunk, 8k resolution, highly detailed"*).
* **Generate Button:** Click to trigger the Stable Diffusion pipeline.
* **Output Gallery:** Displays the generated image ready for download.

---

## 🤝 Connect with Me

* **GitHub:** [@tommysanjaya](https://github.com/tommysanjaya)
* **LinkedIn:** [linkedin.com/in/tommysanjaya](https://linkedin.com/in/tommysanjaya)
