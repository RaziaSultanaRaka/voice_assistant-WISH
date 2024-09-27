# Voice Assistant: WISH

This repository contains the source code for "WISH," a voice assistant built using **LiveKit**, a powerful framework for real-time communication applications. WISH interacts with users using voice commands and responses, leveraging OpenAI for speech recognition (STT), text generation (LLM), and text-to-speech (TTS), along with Silero for voice activity detection (VAD).
## Features

- Voice interaction with users.
- Powered by OpenAI's STT, TTS, and LLM models.
- Integrated with Silero for voice activity detection.

## Prerequisites

- Python 3.x
- Virtual environment set up

## Setup Instructions

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/voice-assistant-wish.git
    cd voice-assistant-wish
    ```

2. **Create and activate a virtual environment**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:

    Ensure that you have a `.env` file with the required API keys and credentials.

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the voice assistant**:

    ```bash
    python main.py
    ```

## Environment Variables

Ensure you have a `.env` file containing the following environment variables:

- `OPENAI_API_KEY`: My OpenAI API key is currently unavailable for payment issue.

## How it works

The voice assistant will:

- Start with a greeting.
- Listen for voice input, process it, and respond using OpenAI's language model.

## Dependencies

- `dotenv`: For loading environment variables.
- `livekit`: For managing voice assistant components.
- `openai`: For integrating with OpenAI APIs.
- `silero`: For voice activity detection (VAD).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
