# PDFVoice

## Overview

The PDFVoice is a Python script project  that reads the content of a PDF file and converts it into an MP3 audio file using text-to-speech technology. This tool is useful for making text content more accessible and creating audio versions of documents.

## Features

- Extracts text from a PDF file
- Converts extracted text to speech
- Saves the audio as an MP3 file
- Configurable speech rate and volume

## Requirements

- Python 3.x
- `pyttsx3` library (for text-to-speech conversion)
- `PyPDF2` library (for reading PDF files)

## Installation

1. **Clone the repository** (if applicable) or download the script:

    ```bash
    git clone https://github.com/your-username/pdf-to-speech-converter.git
    cd pdf-to-speech-converter
    ```

2. **Install the required libraries**:

    ```bash
    pip install pyttsx3 PyPDF2
    ```

## Usage

1. **Update the PDF file path**: With the path to your own PDF file in the script.

2. **Update the output MP3 file path**: With your desired output file name.

3. **Run the script**:

    ```bash
    python pdf_to_speech_converter.py
    ```

   This command will convert the PDF file into an MP3 file with speech.

## Script Details

- **`convert_pdf_to_speech(pdf_path, mp3_path)`**: Main function that handles PDF reading, text extraction, and speech conversion.
  - `pdf_path`: Path to the input PDF file.
  - `mp3_path`: Path where the MP3 file will be saved.

## Configuration

- **Speech Rate**: Adjust the speech rate by modifying the `rate` property in the `speaker.setProperty('rate', 150)` line. The default rate is 150 words per minute.
- **Volume**: Adjust the volume by modifying the `volume` property in the `speaker.setProperty('volume', 1.0)` line. The default volume is 1.0 (full volume).

## Troubleshooting

- **Issue**: "No module named 'pyttsx3'".
  - **Solution**: Ensure that `pyttsx3` is installed. You can install it using `pip install pyttsx3`.

- **Issue**: "No module named 'PyPDF2'".
  - **Solution**: Ensure that `PyPDF2` is installed. You can install it using `pip install PyPDF2`.

## Contributions

- All the suggestions and contributions are welcomed!

## Author

This script is build by Me!
