# aaksAi AI Meeting Assistant

aaksAi is a desktop application that helps you in meetings by providing real-time transcription and AI-generated answers.

## Features

- **Live Transcription**: See your speech as text in real-time
- **AI-Powered Answers**: Get concise and helpful responses using OpenAI's advanced models
- **Always-on-Top**: aaksAi stays visible over other applications
- **Screen Sharing Mode**: Hide aaksAi from screen recordings with a single click
- **Simple Interface**: Minimalist design that stays out of your way

## Usage Instructions

### Basic Controls

- **Start/Stop Recording**: Click the microphone button or press the spacebar
- **Reset Conversation**: Click the refresh button to clear the chat history
- **Hide from Screen Sharing**: Toggle the "Hide" switch to make aaksAi invisible in screen recordings

### Keyboard Shortcuts

- **Spacebar**: Start or stop recording

### Tips for Best Results

1. **Speak Clearly**: For the best transcription quality, speak at a normal pace and volume
2. **Use Short Phrases**: The AI works best with concise, focused questions or statements
3. **Position Properly**: Keep aaksAi visible but out of the way during your meetings
4. **Toggle Screen Sharing**: When sharing your screen, use the Hide toggle to prevent aaksAi from appearing in your presentation

## System Requirements

- **macOS**: 10.14 or newer (Intel and Apple Silicon)
- **Windows**: Windows 10 or newer (64-bit)
- **Memory**: At least 4GB RAM recommended
- **Microphone**: Any working microphone (internal or external)
- **Internet**: Required for AI functionality and transcription

## Privacy & Security

- All audio is processed in real-time and is not stored
- Transcripts and conversations remain on your local device
- API calls to OpenAI follow their privacy and data usage policies

## Troubleshooting

### Microphone Issues

If aaksAi can't hear you:

1. Check your system microphone settings
2. Ensure aaksAi has microphone permissions
3. Try restarting the application

### Performance Issues

If aaksAi is running slowly:

1. Close other resource-intensive applications
2. Ensure you have a stable internet connection
3. Restart the application

## Environment Setup

Store local secrets in a `.env` file and keep them out of git. At minimum, set `OPENAI_API_KEY` and `GOOGLE_APPLICATION_CREDENTIALS` to local values on your machine.

## License

© 2023-2026 aaksAi. All rights reserved.

---

For support or questions, visit: [https://aaksai.com](https://aaksai.com)