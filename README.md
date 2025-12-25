Multilingual Text-to-Speech (TTS) System
A Python-based speech synthesis application that converts text into natural-sounding speech across multiple languages using Google Text-to-Speech (gTTS) and provides an interactive graphical interface for users.

👥 Project Team
Toqa Mahmoud Tawfiq Al-zoubi (32209303103)

Shaden Khaled Mohammad Alshobake (32209303017)

Ghaida Abd-Almajeed Yousef Breitem (32209303009)

Supervised by: Prof. Abdelwadood Mohamad Abdelwadood Mesleh

🚀 Features
Multilingual Support: Seamlessly handles Arabic, English, French, and Spanish.

Adjustable Speech Rate: Includes a "Slow Mode" toggle for educational or accessibility purposes.

Interactive UI: Built-in Jupyter widgets (sliders, text boxes, and buttons) for a code-free user experience.

Instant Playback: Integrated audio player to listen to results immediately within the notebook.

File Export: Automatically generates and saves .mp3 files for external use.

🛠️ Requirements & Installation
To run this project, you need Python and the following libraries:

Bash

pip install gtts pydub ipywidgets
Note: If running in a local environment (outside Colab), you may also need ffmpeg for audio processing.

💻 Technical Implementation
The system core utilizes the gTTS (Google Text-to-Speech) library, which interfaces with Google’s translation API. The logic is divided into:

Speech Engine: A modular function that takes text, lang, and slow parameters.

Interface Logic: Uses ipywidgets to capture user input and IPython.display.Audio for the output stream.

🖥️ How to Use
Open the TTS_Model_Multi_langs.ipynb file in Google Colab or Jupyter Notebook.

Run all cells to initialize the functions and the interface.

In the Interactive UI:

Type your desired text in the text area.

Select the target language from the dropdown menu.

Click the "Convert to Speech" button.

Use the generated audio player to play, pause, or download the sound file.

📖 Interactive Interface Documentation
The interface is designed for accessibility. It includes:

Textarea Widget: Supports long-form text input.

Dropdown Widget: Pre-configured with ISO language codes (ar, en, fr, es).

Toggle Button: Easily switches the slow boolean parameter.

Output Widget: Refreshes dynamically to prevent cluttering the workspace.

📄 License
This project was developed for academic purposes as part of the curriculum under the supervision of Prof. Abdelwadood Mesleh.