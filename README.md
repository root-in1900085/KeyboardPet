# KeyboardPet

A simple keyboard-reactive desktop pet for Windows.

## Requirements

- Windows 10/11 x64
- .NET 10 Desktop Runtime (x64)

Download:
https://dotnet.microsoft.com/download/dotnet/10.0

## Usage

- Run `KeyboardPet.exe`
- Drag the pet to move it
- Use the mouse wheel to resize it
- Right-click the pet for options
- Use the tray icon when click-through mode is enabled

## Customization

Replace the files in the `Assets` folder:

- `idle.png`
- `press1.png`
- `press2.png`

Replace:

- `Sounds/press.wav`

to use your own key sound.

Edit `settings.json` with Notepad to change animation, size,
sound volume, hold delay, etc.

## Features

- Global keyboard input
- Two-frame typing animation
- Squash animation
- Hold-to-squash behavior
- Custom WAV key sound
- Horizontal flip
- Click-through lock mode
- Tray menu
- Live JSON settings reload
- Replaceable PNG/WAV assets
