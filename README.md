# Video to Audio Converter

This script extracts audio from a video file (in `.mp4` format) and saves it as an `.mp3` file using the `moviepy` library in Python.

## Requirements

- Python 3.x
- `moviepy` library

## Installation

First, ensure you have Python 3 installed on your system. Then, you can install the required dependencies using `pip`:

```bash
pip install moviepy
```bash


Usage

    Place the video file (.mp4) in the same directory as the script.
    Update the script to point to your specific video file by modifying the mp4_file variable.

mp4_file = "gurudev.mp4"  # Replace with your video file name
mp3_file = "audio.mp3"    # The output audio file name

Run the script:

python extract_audio.py


After execution, an .mp3 file with the extracted audio will be created in the same directory.

Example

Given a video file named gurudev.mp4, the script will output audio.mp3 containing the audio track from the video.

