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

- `Assets`: replace `idle.png`, `press1.png`, `press2.png`
- `Sounds`: replace `press.wav`
- `settings.json`: edit with Notepad to change size, animation, sound volume, hold delay, etc.

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
