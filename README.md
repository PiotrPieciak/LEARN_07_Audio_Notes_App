# 🎙️ AI Voice Notes App

This is a simple and powerful Streamlit application that allows users to create, edit, and search voice-based notes using OpenAI’s speech-to-text and embedding models.

## 🚀 Live Demo

> ⚠️ You need an OpenAI API key to use this app.  
👉 [Launch the App on Streamlit](https://learn07audionotesappv2.streamlit.app/)  

---

## 🧠 Features

- 🎤 **Voice Recording** – Record and upload audio directly in the app  
- 📝 **AI Transcription** – Uses OpenAI Whisper API to transcribe speech to text  
- ✏️ **Note Editing** – Clean and edit the note before saving  
- ☁️ **Cloud Storage** – Save notes to a vector database (Qdrant)  
- 🔍 **Semantic Search** – Search your notes using OpenAI embeddings, even without exact keywords  
- 📱 **Clean UI** – Simple and intuitive layout powered by Streamlit

---

## 📦 Requirements

The app uses the following technologies:

- Python 3.11
- Streamlit
- OpenAI API (Whisper + Embeddings)
- Qdrant (vector DB)
- Additional dependencies listed in `requirements.txt`
- Additional packages listed in `packages.txt`

To install the Python dependencies:

```bash
pip install -r requirements.txt
```

## 📌 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/PiotrPieciak/LEARN_07_Audio_Notes_App
   cd your-repo-name
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Make sure `ffmpeg` is installed (refer to `packages.txt`):
   - On macOS: `brew install ffmpeg`
   - On Ubuntu: `sudo apt install ffmpeg`
   - On Windows: [FFmpeg download](https://ffmpeg.org/download.html)
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
## 🙋‍♂️ About

This app was built as a personal productivity tool and a demo of integrating real-time audio processing, OpenAI services, and semantic search—all wrapped in a minimal Streamlit frontend. Perfect for note-taking, journaling, or summarizing meetings with your voice.

✅ TODO
- Add support for more languages
- Improve search filtering
- Export notes to PDF or Markdown

📄 License
MIT License. Feel free to use and modify.