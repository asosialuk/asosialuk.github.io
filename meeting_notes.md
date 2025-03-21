## Automated Meeting Notes Generator

**Project description:** The project implements a Streamlit web application that automates the process of generating meeting notes from audio recordings. 

### 1. Highlights: 
The application allows users to upload files (WAV, MP3, MP4) and automatically generates details meeting notes. It utilises: 
* Whisper (OpenAI): for audio transcription, speech to text
* Pyannote_audio: for speaker diarization, indetification and labeling different speakers within the audio
* OpenAI API (GPT-3.5-turbo): for NLP, extracting key information and structuring the meeting notes
* Streamlit: for creating an interactive and user-friendly web interface
* pydub: for audio format conversion 
* FPDF: for PDF generation
<img src="images/Meeting_streamlit1.png?raw=true"/>
<img src="images/Meeting_streamlit2.png?raw=true"/>

### 2. Key Observation:
* Automated Transcription and Diarization: it transcribes audio and idetntifies speakers, providing a clear and organized transcript
* Structured Meeting notes: it extracts key meeting points, including objectives, discussion details, actions and next meeting dates
* User-friendly Interface: streamlit provides an interface for uploading audio files and viewing results
* PDF and text dowload: users can download meeting notes in both text and PDF formats for easy sharing and archiving

### 3. Data sources:
* User-uploaded audio files (WAV, MP3, MP4)
* Pretrained Whisper model (OpenAI)
* Pre_trained Pyannote.audio speaker diarization model (Hugging Face)
* OpenAI API (GPT-3.5-turbo)

### 4. Further Improvements:
* Allowing the users to choose what information they want to get from the meeting
* Integrate the meeting templates 
* Develop a system to automatically track actions and assignees, with reminders and progress updates
* Integrate the notes with task management systems
* Keep the records of audios and notes on cloud storage services
* Optimise the app's performance
* Refine the usage of the Openai API to reduce costs 


  








