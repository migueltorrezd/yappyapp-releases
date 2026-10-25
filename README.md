# YappYapp

YappYapp is a local-only dictation app for your Mac. Press Option+Space, talk, and verified text lands where your cursor is, with on-device Whisper and Parakeet transcription so your voice never leaves your Mac.

**Website, setup guide and download: [yappyapp.app](https://yappyapp.app/en/download)**

This repo hosts the public downloads, the update feed and the issue tracker. The source code is at [migueltorrezd/yappyapp](https://github.com/migueltorrezd/yappyapp).

## Install via DMG

1. Download the latest `YappYapp-x.y.z.dmg` from the [Releases page](https://github.com/migueltorrezd/yappyapp-releases/releases/latest) or from [yappyapp.app](https://yappyapp.app/en/download).
2. Open the DMG and drag YappYapp into your Applications folder.
3. Double-click YappYapp. It is signed with a Developer ID and notarized, so it opens like any other app.

Step-by-step setup (microphone, accessibility, picking a model): [yappyapp.app/en/how-to-use](https://yappyapp.app/en/how-to-use).

YappYapp needs an Apple Silicon Mac with macOS 14 or newer.

## Install via Homebrew

```
brew install --cask migueltorrezd/tap/yappyapp
```

## Updates

The app updates itself. Signed updates are delivered through Sparkle, so you get new versions verified and in place without hunting down a download.

Updating straight from 0.3.x: macOS asks for Accessibility and Microphone access once more, because 0.4.0 changed how the app is signed. Turn YappYapp back on in System Settings > Privacy & Security > Accessibility and > Microphone.

## What to test as a beta friend

- Dictate into a few different apps (notes, chat, your editor, a browser field) and see where the text lands.
- Try the languages you actually work in and check how it handles them.
- Teach it your words in the Words tab: product names, clients, acronyms. Watch it correct them across transcripts.
- Meet your pet. Dictate a bit and see it level up.

If something breaks, please [open an Issue](https://github.com/migueltorrezd/yappyapp-releases/issues). The app also has built-in diagnostics for mic, models, paste, and permissions, so mention that output in your report and it will save us both time.
