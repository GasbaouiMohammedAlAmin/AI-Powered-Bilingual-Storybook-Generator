# AI-Powered-Bilingual-Storybook-Generator
Generate engaging children’s storybooks with AI — in both English and Arabic, complete with illustrations!

## 🌟 Overview
In this project, we demonstrate how to build an AI-powered storybook generator using Google Colab. The system creates engaging bilingual stories for 8-year-old children in both English and Arabic. Each generated page includes: 
- ✏️ A simple English sentence,
- 🌍 It's Arabic translation.
- 🎨 A representative image that visually illustrates the story content.

  To achieve this, we leverage free and powerful AI models: **Meta-Llama-3-8B-Instruct** for text generation and **Stable Diffusion XL (SDXL) Base 1.0** for image creation. Additionally, we use the Gradio framework to design an interactive user interface, allowing users to select story themes such as _“Friendship and Desert Adventure,” “Animals in the Forest,” or “Space Adventure.”_ The final output is automatically compiled into a well-structured PDF storybook.

This project is ideal for:

- AI enthusiasts
- Educators and content creators
- Students learning generative AI

## 🧠 Key Features

- ✨ Bilingual Story Generation (English + Arabic)
- 🎨 Automatic Image Generation (Stable Diffusion)
- 📄 PDF Storybook Export
- 🔤 Arabic Text Rendering (RTL + reshaping support)
- 🌐 Interactive UI using Gradio
- ⚡ Runs on Google Colab (no local setup needed)

## 🏗️ System Pipeline

```text
User Input (Theme)
        ↓
Story Generation (LLM)
        ↓
Image Prompt Extraction
        ↓
Image Generation (Stable Diffusion)
        ↓
PDF Creation (ReportLab)
        ↓
Final Storybook 🎉
```

## ⚙️ Technologies Used
- 🐍 Python
- 🤗 Hugging Face Inference API
- 🖼️ Stable Diffusion (Text-to-Image)
- 📄 ReportLab (PDF generation)
- 🌐 Gradio (User Interface)
- 🔤 arabic-reshaper + python-bidi

## 🚀 How to Run
### ▶️ Google Colab

1. Open the notebook:
```text
AI Storybook Generator.ipynb
```
2. Add your Hugging Face API key:
```text
HF_TOKEN = "your_api_key_here"
```
3. Run all cells
4. Launch the Gradio interface
5. Select a theme and generate your storybook 📚

## 🧪 Example Output
```text
Page 1:
English: The little camel walked in the desert.
Arabic: سار الجمل الصغير في الصحراء.
Image: (AI-generated illustration)
```
## 📱 video explanation

## 🔧 project limitation
- There are some issues with Arabic typography due to the free LLM. 
- There are some limitations in image generation, and we cannot maintain the same personality and character consistency across all images.

## 🔮 Future Improvements
- 🔊 Add voice narration (TTS)
- 🎥 Convert story to video
- 📱 Deploy as web/mobile app
- 🧠 Fine-tune Arabic models
- 🎭 Character consistency across pages

## ⭐ Support

If you like this project:

- ⭐ Star this repository
- 🔁 Share it
- 🤝 Contribute

