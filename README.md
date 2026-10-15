# NovaAI

NovaAI is a mobile-friendly AI assistant prototype designed to run as a web app and be deployable through GitHub Pages.

## Current prototype

- Chat interface optimized for Android and desktop
- Gemini API integration using a user-provided API key
- Voice input and text-to-speech support where the browser supports them
- Text-file upload support
- New-chat and settings controls

## Important notes

- This is an early web prototype, not a native Android APK.
- AI responses require a valid Gemini API key and internet access.
- Do not put private API keys into public source code. The prototype stores the key in browser session storage; for a production app, use a secure backend.
- Any market data or other external data must be clearly labeled as simulated unless connected to a licensed live data provider.

## Run locally

Open `index.html` in a modern browser. Some browser features, especially voice input, may require HTTPS and browser support.
