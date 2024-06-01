# Multilingual-translation-Summarization

Multilingual-translation-Summarization
Overview
This project is an Multilingual-translation-Summarization that allows users to transcribe, translate, and summarize audio files. The application is built using Streamlit for the web interface and leverages the Whisper model for accurate transcription and language detection. Additional functionalities include translation to multiple languages and text summarization.

Features
Transcription: Converts audio files into text using the Whisper model.
Language Detection: Detects the language of the transcribed text.
Translation: Translates the transcribed text into various target languages.
Summarization: Summarizes the transcribed text to extract key information.
Technologies Used
Streamlit: Web framework for the user interface.
Whisper: Model for transcription and language detection.
Langdetect: Library for detecting the language of the text.
Supporting Libraries: For translation and summarization.
Installation
Clone the repository:

bash
Copy code
gh repo clone Rishi-spec-art/Multilingual-translation-Summarization

Create a virtual environment:
And Download Transformers, langdetect, whisper, etc.


python
Copy code
import whisper
model = whisper.load_model("medium")
Usage
Run the Streamlit application:

bash
Copy code
streamlit run GUI.py
Upload an Audio File: Click on the "Upload an audio file" button and select an MP3 file from your device.

Transcribe the Audio: Click the "Transcribe" button to convert the audio content to text.

Translate the Text: Select a target language from the dropdown list and click the "Translate" button to translate the text.

Summarize the Text: Click the "Summarize" button to generate a summary of the transcribed text.

Project Structure
GUI.py: The main file for the Streamlit application.
spc_2_txt.py: Contains the Model class for transcription and language detection.
requirements.txt: Lists the dependencies required for the project.
Contributing
Contributions are welcome! Please open an issue or submit a pull request with your improvements.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
[Streamlit](https://streamlit.io/)
[Whisper](https://pypi.org/project/openai-whisper/)
[Langdetect](https://pypi.org/project/langdetect/)
