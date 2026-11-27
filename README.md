# AI Reel Generator

An AI-powered web application that generates short-form videos from images and text using automated text-to-speech and video processing.

## Overview

AI Reel Generator simplifies short-form content creation by combining images and AI-generated audio into vertical videos suitable for social media platforms.

## Features

- Image uploading through a web interface
- AI-powered text-to-speech conversion
- Automated reel generation
- Vertical video output (1080 × 1920)
- Audio and image integration using FFmpeg
- Secure API key management using environment variables

## Tech Stack

- Python
- Flask
- HTML
- CSS
- Text-to-Speech API
- FFmpeg
- Git and GitHub

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/om-pandey-builds/AI_Reel_Generator.git
cd AI_Reel_Generator
```

### 2. Install Python dependencies

```bash
pip install -r requirements.txt
```

### 3. Install FFmpeg

For Windows:

```bash
winget install --id Gyan.FFmpeg -e
```

Verify the installation:

```bash
ffmpeg -version
```

### 4. Configure environment variables

Create a .env file using .env.example as a reference.

```env
API_KEY=your_api_key_here
```

### 5. Run the application

Start the Flask application:

```bash
python main.py
```

Open another terminal and start the video generation process:

```bash
python generate_process.py
```

Open http://127.0.0.1:5000 in your browser if Flask uses the default port.

## How It Works

1. Upload images through the web interface.
2. Enter text for voice generation.
3. Convert text into audio using the API.
4. Process images and audio using FFmpeg.
5. Generate the final reel in MP4 format.

## Future Enhancements

- AI-generated video captions
- Multiple voice options
- Custom video templates
- Background music customization
- Adjustable video duration
- Cloud deployment

## Author

Om Pandey

GitHub: https://github.com/om-pandey-builds
