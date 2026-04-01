# Quick Start Guide

This project is focused on **local-first** and **privacy-first** principles. To use it at full capacity, a few things need to be set up before getting started. This guide will walk you through each one.

---

## 1. AI Feature — Ollama Setup

The AI feature relies on **Ollama** to run large language models locally on your machine.

### Steps:
1. Download and install Ollama from the official website: [https://ollama.com/](https://ollama.com/)
2. Once installed, it is recommended to pull the **Granite 4** model, which works perfectly and is very efficient on legacy and older hardware:
   👉 [https://ollama.com/library/granite4](https://ollama.com/library/granite4)
3. Run the following command in your terminal to pull the model:
   ```bash
   ollama pull granite4
   ```
4. Make sure Ollama is running before launching the app.

> Ollama works with most open-source models, so you are free to use any compatible model of your choice.

<img width="1304" height="871" alt="image" src="https://github.com/user-attachments/assets/4cdf0cac-5934-448f-9b7d-58fdc5052a5d" />


---

## 2. Reader Mode (Text-to-Speech) — Piper TTS Setup

The reader mode relies on **Piper TTS**, an open-source text-to-speech project, to read your notes aloud.

### Steps:
1. Open the app and navigate to the **Download** section inside the settings.
2. Select your preferred TTS voice model from the list.
3. Click **Download** to install the model directly from within the app.
4. Once downloaded, the reader mode will be ready to use.

> No manual file placement is needed — the app handles the download and setup automatically.

<img width="1304" height="871" alt="image" src="https://github.com/user-attachments/assets/45141ffb-caad-4d76-9f7b-019bf68fe86a" />


---

## 3. Speech-to-Text — Vosk Model Setup

The speech-to-text feature uses **Vosk**, which works similarly to Piper but requires a manual setup step.

### Steps:
1. Download your preferred Vosk model from the official Vosk models page:
   👉 [https://alphacephei.com/vosk/models](https://alphacephei.com/vosk/models)
2. Open the app's data folder by clicking the **folder icon** in the app.
3. Place the downloaded Vosk model inside the data folder.
4. Restart the app — the speech-to-text feature will detect the model automatically.

<img width="1304" height="871" alt="image" src="https://github.com/user-attachments/assets/bedb2419-e910-4c99-b1b2-83f745ebbdce" />


---

Once all three components are set up, you are ready to use the app at its full potential. Enjoy a fully local, private, and powerful note-taking experience!
