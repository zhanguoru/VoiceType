# Whisper Hotkey (Windows)

A lightweight Windows hotkey tool for voice-to-text powered by **faster-whisper**.

Press a hotkey, speak, release — your speech is transcribed and pasted automatically.

---

## Features

- Global hotkey (no need to switch windows)
- Fast and accurate speech-to-text using Whisper
- Offline transcription after first-time setup
- Simple UI with optional support QR code
- No installation required (portable)

---

## System Requirements

- Windows 10 / Windows 11 (64-bit)
- Microphone (built-in or external)
- Internet connection **only required for first run**

---

## Download & Run

1. Download the latest release from the **Releases** page
2. Extract the zip file
3. Run `whisper_hotkey.exe`

> ⚠️ **Important:**  
> Do not delete or move any files inside the folder.  
> The program must stay in its original directory.

---

## First Launch (Important)

### Why is the first run slow?

This is **normal behavior**.

On the first launch and the first transcription:

- The Whisper model will be downloaded automatically
- Model size can be hundreds of MB
- Initialization may take **1–3 minutes**, depending on your network and hardware

After the model is downloaded:

- Startup becomes much faster
- Voice transcription becomes near-instant

> You only need to wait once.

---

## Usage

1. Press **F8** → you will hear a short beep (recording starts)
2. Speak into your microphone
3. Release **F8** → another beep (recording stops)
4. The transcribed text will be pasted automatically

---

## Microphone & Permissions

- On first run, Windows may ask for microphone access  
  → Please click **Allow**
- If no sound is recorded, check:
  - Windows microphone privacy settings
  - Default input device in Windows

---

## Offline Usage

- Internet is required **only for the first run**
- After the model is downloaded, the program works fully offline

---

## Known Notes

- First transcription may feel slower than later ones
- Antivirus software may warn about unknown executables  
  (this is common for unsigned portable apps)

---

## Support the Project

If you find this tool useful, you can support development via the QR code inside the app ❤️

---

## Disclaimer

This project is provided as-is, without warranty.  
Use at your own risk.

---

## License

MIT License
