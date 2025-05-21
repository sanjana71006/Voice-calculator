📢 Voice-Calculator
Voice-Calculator is a Python-based project that performs arithmetic operations based on voice input and provides the result as audio output. This project integrates speech recognition, text-to-speech conversion, and expression evaluation in a seamless audio-driven calculator experience.

🎯 Features
🎤 Converts voice/audio input into text using speech recognition
🧮 Extracts and evaluates arithmetic expressions from the recognized text
🔊 Converts the result back to speech and plays it as audio output
🛠️ Supports operations like addition, subtraction, multiplication, and division

🧰 Tech Stack
Python
gTTS (Google Text-to-Speech)
SpeechRecognition
PyDub

Google Colab (for interactive demos)

📂 How It Works
Upload or record an audio file containing a spoken arithmetic expression (e.g., "seven plus five").
The system transcribes the audio to text using Google’s SpeechRecognition.
A regular expression is used to extract and evaluate the arithmetic expression.
The result is converted to audio using gTTS and played/saved as a response.

📦 Use Cases
Educational tools for visually impaired or early learners

Voice-controlled calculator for smart assistants

Audio-based input/output interfaces in embedded systems
