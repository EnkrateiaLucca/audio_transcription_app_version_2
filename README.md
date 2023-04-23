# Audio Transcription App using Whisper

This is a Python project that allows you to transcribe an audio file using the Whisper library and a user-friendly interface built with Gradio.

# Installation

Clone the repository:

```
git clone https://github.com/your-username/audio-transcription-app.git
```

Navigate to the project directory:

```
cd audio-transcription-app
```

Create a virtual environment (optional but recommended), I tested my script on
Python 3.10:

```
python3 -m venv env
source env/bin/activate
```

or with conda:

```
conda create -n audio_app

conda activate audio_app
```

Install the required packages:

```
pip install -r requirements.txt
```

Start the application:

```
python app.py
```

Upload an audio file (in .mp3, .wav, or .flac format).

Click the "Submit" button to start the transcription process.

Wait for the application to transcribe the audio file and display the results.