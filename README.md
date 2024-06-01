# Multilingual-translation-Summarization

## Multilingual-translation-Summarization<br/>
#### Overview<br/>
This project is an `Multilingual-translation-Summarization` that allows users to transcribe, translate, and summarize audio files. The application is built using Streamlit for the web interface and leverages the Whisper model for accurate transcription and language detection. Additional functionalities include translation to multiple languages and text summarization.<br/>

#### Features<br/>
`Transcription`: Converts audio files into text using the Whisper model.<br/>
`Language Detection`: Detects the language of the transcribed text.<br/>
`Translation`: Translates the transcribed text into various target languages.<br/>
`Summarization`: Summarizes the transcribed text to extract key information.<br/>
#### Technologies Used<br/>
**Streamlit**: Web framework for the user interface.<br/>
**Whisper**: Model for transcription and language detection.<br/>
**Langdetect**: Library for detecting the language of the text.<br/>
**Supporting Libraries**: For translation and summarization.<br/>
#### Installation<br/>
Clone the repository:<br/>
bash<br/>
Copy code<br/>
gh repo clone Rishi-spec-art/Multilingual-translation-Summarization<br/>
<br/>
#### Create a virtual environment:<br/>
And Download Transformers, langdetect, whisper, etc.<br/>
<br/>

python<br/>
Copy code<br/>
import whisper<br/>
model = whisper.load_model("medium")<br/><br/>
Usage<br/>
#### Run the Streamlit application:<br/>

bash<br/>
Copy code<br/>
streamlit run GUI.py<br/>
Upload an Audio File: Click on the "Upload an audio file" button and select an MP3 file from your device.<br/>

Transcribe the Audio: Click the "Transcribe" button to convert the audio content to text.<br/>

Translate the Text: Select a target language from the dropdown list and click the "Translate" button to translate the text.<br/>

Summarize the Text: Click the "Summarize" button to generate a summary of the transcribed text.<br/>

#### Project Structure<br/>
GUI.py: The main file for the Streamlit application.<br/>
spc_2_txt.py: Contains the Model class for transcription and language detection.<br/>
requirements.txt: Lists the dependencies required for the project.<br/>
Contributing<br/>
Contributions are welcome! Please open an issue or submit a pull request with your improvements.<br/>

#### License<br/>
This project is licensed under the MIT License. See the LICENSE file for more details.<br/>
<br/>
#### Acknowledgements<br/>
[Streamlit](https://streamlit.io/)<br/>
[Whisper](https://pypi.org/project/openai-whisper/)<br/>
[Langdetect](https://pypi.org/project/langdetect/)<br/>
