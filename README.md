# Meeting Assistant - Minutes of Meeting (MoM) Generator

## Overview
This project is a Streamlit-based Meeting Assistant that processes audio recordings of meetings and generates concise Minutes of Meeting (MoM). It utilizes the AssemblyAI API for audio transcription and automatic summarization.

## Features
- Upload an audio file of a meeting.
- Automatically transcribes the audio using AssemblyAI.
- Extracts main themes and topics discussed.
- Generates summarized meeting notes with timestamps.
- Allows users to navigate through meeting sections.

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Pip package manager

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/meeting-assistant.git
   cd meeting-assistant
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up API authentication:
   - Open `config.py` and add your AssemblyAI API key:
     ```python
     auth_token="your_assemblyai_api_key"
     ```

## Usage
1. Run the Streamlit application:
   ```bash
   streamlit run MoM.py
   ```
2. Upload an audio file through the web interface.
3. Wait for the transcription to complete.
4. View and explore the summarized meeting notes.

## File Structure
- `MoM.py` - Main Streamlit app that handles file upload and displays results.
- `get.py` - Handles API calls for uploading and processing audio files.
- `config.py` - Stores authentication token for AssemblyAI API.

## API Used
- [AssemblyAI](https://www.assemblyai.com/) for speech-to-text and summarization.

## Future Improvements
- Add support for real-time transcription.
- Integrate with Google Meet, Zoom, and Microsoft Teams.
- Improve UI for better user experience.

## License
This project is open-source and available under the MIT License.

## Deployment Link 
https://gururaj8756-meeting-mom-v5aih0.streamlit.app/
