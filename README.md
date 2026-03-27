# ttsstreamers1


A free, lightweight text-to-speech app built for mute streamers. Type what you want to say and it speaks it instantly — no accounts, no internet, no subscriptions.



Features

Instant TTS — type a message, press Enter, it speaks
Saved phrases — store your most used lines (Hello chat, BRB, GG, etc) and speak them in one click
History — last 50 things you said, click any to repeat
Global hotkeys — speak and stop without clicking, works even while gaming

Ctrl+Shift+Space — speak
Ctrl+Shift+S — stop


Voice, speed & volume controls — uses your Windows installed voices
OBS & Discord routing — works with VB-Cable for full audio routing
Dark UI — designed for streamers, easy to read at a glance
Double-click launcher — no terminal needed


Setup
1. Install Python
Download from python.org — tick "Add to PATH" during install.
2. Install dependencies
Open Command Prompt and run:
pip install pywin32 keyboard
3. Download the files
Put both files in the same folder:

streamer_tts.py
START TTS.bat

4. Launch
Double-click START TTS.bat — that's it.

OBS / Discord Routing
To make your TTS voice come through as a microphone in OBS and Discord:

Download VB-Cable for free at vb-audio.com/Cable
Install it and set CABLE Input as your Windows default playback device
OBS → Add source → Audio Input Capture → select CABLE Output
Discord → Settings → Voice & Video → Input Device → CABLE Output

Your TTS voice will now appear as a microphone to both apps.

Hotkeys
HotkeyActionEnterSpeak typed messageShift+EnterNew line in messageEscapeStop speakingCtrl+Shift+SpaceSpeak (global, works in-game)Ctrl+Shift+SStop (global)

Requirements

Windows 10 or 11
Python 3.8+
pywin32
keyboard


Roadmap / Ideas
Got a feature idea? Open an Issue and let me know!
Some things being considered:

Always on top mode
Per-phrase hotkeys (F1, F2...)
Minimize to system tray
Import / export phrase lists
Voice changer / pitch shift

