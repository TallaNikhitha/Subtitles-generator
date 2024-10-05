# Subtitle Generator using NLP

This project is a **Subtitle Generator** built using **Natural Language Processing (NLP)** techniques. The main objective of the project is to generate subtitles from video/audio files, supporting multiple languages such as English and Hindi.

# Features
- **Speech-to-Text Transcription**: Extracts speech from videos and converts it into text using Automatic Speech Recognition (ASR).
- **Multi-Language Support**: Generates subtitles in both **English** and **Hindi**.
- **Text Preprocessing**: Cleans and processes the transcribed text for better subtitle quality.
- **Custom Subtitle Formatting**: Outputs the generated text into standard subtitle formats such as `.srt`.
- **NLP Integration**: Enhances accuracy using NLP models for cleaner transcription and translation.
  
# Requirements
To run the project, you need to have the following dependencies installed:

- Python 3.7+
- `pandas`
- `numpy`
- `tensorflow`
- `transformers`
- `gradio`
- `moviepy` (for video/audio extraction)
- `speech_recognition` (for speech-to-text conversion)

You can install these dependencies by running:
```bash
pip install -r requirements.txt
```

# Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Subtitle_Generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Subtitle_Generator
   ```
3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

# How to Use
1. Upload your video file to the system.
2. Run the subtitle generator to extract audio and transcribe the text.
3. The generated subtitles will be provided in both **English** and **Hindi**.

You can run the project via the Jupyter notebook provided (`Subtitle_generator.ipynb`) or integrate it into your pipeline.

# Example Output
An example `.srt` subtitle file is provided in the `examples/` folder.

# Acknowledgements
This project was built using resources from:
- **Hugging Face** for pre-trained NLP models.
- **MoviePy** for video and audio processing.
- **Google Speech API** for ASR (Automatic Speech Recognition).
