
#  MindMate:AI — Your Trustable Chat Companion

MindMate:AI is an emotionally intelligent chatbot that provides motivation, mental wellness support, and a safe space for users to express themselves. It uses **Gemini AI (gemini-1.5-flash-001)** for real-time, empathetic interactions and offers multiple personality modes, emotion-aware conversation, and voice output.

---

##  Features

- ** Gemini AI Integration**  
  Uses Google's `gemini-1.5-flash-001` model to power empathetic and human-like conversations.

- ** Personality Modes**  
  Choose how the bot interacts with you:
  - **Therapist** – Calm and empathetic
  - **Motivational Coach** – Energetic and inspiring
  - **Friendly Buddy** – Lighthearted and cheerful
  - **Wise Mentor** – Thoughtful and philosophical

- ** Emotion Detection**  
  Detects emotions from text input and adjusts responses accordingly (happy, sad, angry, neutral).

- ** Voice Output (TTS)**  
  Converts chatbot responses into natural-sounding speech using `gTTS`.

- ** Audio Input Support**  
  Upload `.wav` audio files to transcribe voice into text (using `SpeechRecognition`).

- ** Clean UI Interface (Kaggle/Colab)**  
  Modern, responsive interface built using widgets, closely mimicking ChatGPT with a dark theme.

---

##  Tech Stack

| Component            | Technology                |
|----------------------|---------------------------|
| LLM                  | Gemini 1.5 Flash API      |
| UI                   | ipywidgets + Colab/Kaggle |
| Emotion Detection    | Custom Python Logic       |
| Voice Output         | gTTS                      |
| Audio Transcription  | SpeechRecognition         |

---

##  UI Preview

![output2](https://github.com/user-attachments/assets/d962b487-58b8-4594-b6fe-b677561d8714)


---

##  How to Use

1. **Open the Notebook** in Kaggle or Colab.
2. **Set your Google API Key** as a secret variable (Kaggle) or directly in the notebook.
3. **Choose a personality mode** from the dropdown.
4. **Type your message** and start chatting with MindMate:AI.
5. **Optionally**, upload a `.wav` audio clip and let the bot transcribe and respond.
6. Enjoy personalized responses and voice-based feedback.

---

##  API Key Setup

Make sure to store your Gemini API Key securely. On Kaggle:

- Go to **Add-ons > Secrets**.
- Create a new secret with the name `GOOGLE_API_KEY`.

---

##  Project Goals

- Provide emotional companionship to users in need of motivation or comfort.
- Enable context-aware conversations using emotion detection.
- Combine chat with speech interaction for a richer experience.

---

##  Feedback & Improvements

We’d love your feedback and ideas! Drop a comment or suggest improvements as we continue building MindMate:AI into the perfect motivational partner. 🌈✨

---

## Author

Developed with ❤ by **Lenin**  
Powered by Gemini API and Colab Widgets

---

##  License

This project is for educational purposes. Gemini API usage is subject to [Google's Terms of Service](https://ai.google.dev/terms).
