# Playdio

## Project Goal
Playdio is a local text-to-speech application designed to convert written texts into audio files. The goal is to provide a free and convenient alternative to paid online TTS services, especially for longer texts such as books and documents.

## MVP Features
- Select and read `.txt` files.
- Split longer texts into manageable chunks.
- Convert text into speech using a local TTS model.
- Combine generated audio chunks and save the result.
- Provide a basic UI for file selection and conversion.
- Play, pause, seek, and control audio playback speed.

## Future Plans (V2.0+)
- Support PDF and EPUB files.
- Automatically format text and detect chapters.
- Offer multiple voice options.

## Tech Stack
- **Language:** Python
- **UI:** Streamlit
- **TTS:** Local Qwen3-TTS with MLX-Audio
- **Storage:** Local text and audio files

## Project Status
Working on Milestone 2

## Documentation
Project planning documents, including the Eisenhower Matrix, build milestones, and system diagram, are available in the `doc/` directory.