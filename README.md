# NovaAI

NovaAI is a mobile-friendly AI assistant web prototype for Android and desktop browsers.

## Features in this first version

- Responsive chat interface
- Google Gemini API integration using a key you provide
- Voice dictation where supported by the browser
- Attach and include small text, Markdown, CSV, JSON, HTML, CSS, and JavaScript files in a prompt
- New-chat and settings controls
- GitHub Actions workflow to publish the static site to GitHub Pages

## Publish the app

1. Open the repository **Settings** on GitHub.
2. Open **Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Open the **Actions** tab and check the **Publish NovaAI to GitHub Pages** workflow. If it has not run, use **Run workflow** or push a new commit.
5. When deployment succeeds, the Pages URL will appear in the workflow run and in Settings → Pages. It should be `https://hotshooter14-png.github.io/NovaAI/`.

## Connect AI responses

1. Open the deployed site.
2. Tap the gear icon.
3. Paste your own Gemini API key and save.

AI responses need an internet connection and a valid key. The prototype keeps the key in the current browser session; it is not a secure production credential store. Do not commit API keys to this repository. For a public production service, put model calls behind a secure backend with authentication and usage limits.

## Limitations

This is a working first web prototype, **not a native Android APK** and not a full ChatGPT replacement. Voice dictation depends on browser support. File attachments are limited to text-like files under 200 KB. It does not include image understanding, persistent cloud chat history, account login, payments, or a private backend yet. Keep all API keys private.

## Run locally

Open `index.html` in a modern browser. Some browser features may require HTTPS.
