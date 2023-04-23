# Automation

To make it easier for users to run the application on any machine (Windows, macOS, or Linux), you can create a Bash script that automates the installation and running of the application.

Create a new file called run.sh:

arduino
Copy code
touch run.sh
Open the file in a text editor and add the following lines:

bash
Copy code
#!/bin/bash

# Clone the repository
git clone https://github.com/your-username/audio-transcription-app.git
cd audio-transcription-app

# Create a virtual environment and install packages
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt

# Download the pre-trained Whisper model
python -m whisper download base

# Run the application
python app.py
Save the file and close the text editor.

Make the script executable:

arduino
Copy code
chmod +x run.sh
Now, users can run the application with just one command:

arduino
Copy code
./run.sh
The script will automatically clone the repository, install the required packages, download the pre-trained Whisper model, and run the application.