# Spotlight Local AI

A dead-simple local AI chat app for Windows, powered by the LFM2.5-VL-1.6B model running 100% on your machine via llama.cpp.

- No login, no account, no subscription
- Vision: attach images (png/jpg/gif/webp/bmp)
- Smart routing: if a question needs current internet info, the app searches the web and cites sources; otherwise it answers fully offline

## Download / install

1. Download `SpotlightLocalAI-Setup.exe` from the [latest release](https://github.com/aayushman-tech/spotlight-local-ai/releases/latest)
2. Run it. Installs per-user (no admin rights needed) to `%LocalAppData%\Programs\Spotlight Local AI`
3. First launch loads the model — the status dot turns green when ready

Silent install (for IT/automation): `SpotlightLocalAI-Setup.exe /VERYSILENT /NORESTART`

## Privacy Policy

Last updated: October 24, 2026

### 1. Overview
Spotlight Local AI is a chat application that runs an AI model (LFM 2.5 VL 1.6B) entirely on your Windows device. The app is designed so that your questions, answers, and images stay on your machine.

### 2. Information the app does NOT collect
- We do not collect, store, or transmit your name, email, or any personal information.
- The app requires no account, login, or registration.
- We do not collect usage statistics, telemetry, crash reports, or advertising identifiers.
- Your conversations and attached images are processed locally on your device and are not uploaded to us or to any server.

### 3. When a web search happens
Before answering, the app decides whether your question needs current internet information (for example news, weather, or prices). If it does, the app performs a search using an anonymous web request and reads public results to answer you.
- These searches are not tied to your identity — no account or personal data is attached to them.
- If the question can be answered from the local AI's own knowledge, no internet request is made at all.

### 4. Third-party technology
The app uses the open-source llama.cpp engine to run the model locally. No third-party analytics or advertising SDKs are included.

### 5. Children
The app is not directed at children under 13 and does not knowingly collect any personal information from anyone.

### 6. Data deletion
Nothing is stored on our servers, because the app sends no conversational data to us. Closing the app ends the session; conversations exist only within the app window on your device.

### 7. Changes to this policy
If this policy changes, the updated version will be included with the app or posted on this repository.

### 8. Contact
If you have questions about this privacy policy, contact via the GitHub repository issues page.
