🎙️ AI Personal Voice Assistant
An intelligent, voice-activated personal assistant built with Python and tkinter. This assistant can perform various tasks like web searches, playing music, reading Wikipedia summaries, telling jokes, giving weather updates, capturing photos, and more — all through your voice!

🧠 Features
🎤 Real-time voice recognition using speech_recognition

🗣️ Voice responses with pyttsx3 (Text-to-Speech)

🌐 Wikipedia search and spoken summary

📺 Play songs on YouTube via pywhatkit

☁️ Get live weather updates using OpenWeatherMap API

😄 Tell programming jokes using pyjokes

🔍 General question answering with DuckDuckGo API

📷 Take a photo using your webcam (ecapture)

🌐 Open websites like Google, Gmail, YouTube, and Stack Overflow

🖥️ GUI built with tkinter (includes Start/Stop Listening buttons and visual feedback)

🛠️ Libraries Used

Library	Purpose
speech_recognition	Capturing and converting speech to text
pyttsx3	Converting text to speech
wikipedia	Fetching summaries from Wikipedia
pywhatkit	Playing YouTube songs
pyjokes	Fetching jokes
requests	Fetching data from APIs
webbrowser	Opening URLs
tkinter	GUI framework
ecapture	Capturing images via webcam
🚀 How to Run
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/ai-voice-assistant.git
cd ai-voice-assistant
2. Install Dependencies
Make sure you have Python installed (preferably 3.10+).

Install required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Or install individually:

bash
Copy
Edit
pip install speechrecognition pyttsx3 wikipedia requests pywhatkit pyjokes ecapture
3. Run the Application
bash
Copy
Edit
python virtual.py
🔑 Notes
Ensure your microphone and speakers are working.

Replace the placeholder API key in the code with your OpenWeatherMap API Key.

Use Python 3.10+ for best compatibility.

Works best in quiet environments for accurate speech recognition.

💡 Future Enhancements
Wake-word detection (e.g., "Hey G-One")

Integration with Google Calendar or Emails

Multilingual support

AI-powered chatbot responses using GPT or other models

🤝 Contributing
Feel free to fork the repo and contribute! Suggestions, pull requests, and feedback are always welcome.

📜 License
This project is open-source and free to use under the MIT License.
