# Bunbun!

Bunbun is an interactive 3D desktop companion for Windows, inspired by BonziBuddy, Microsoft Agent, and nostalgic virtual pets of the Windows XP era. It lives as a floating, draggable character on your desktop featuring real-time 3D pixel-art animations, voice recognition, speech bubbles, an offline AI assistant, retro arcade minigames, a media deck, and PC utility tools.

Built with Electron and Node.js.

---

## Features

### Desktop Companion
- **3D Character Animations:** Smooth real-time states including idle breathing, ear twitches, blinking, talking mouth flaps, waving, grooving to music, sweeping/cleaning, sleeping, and animated burrowing/emerging from ground holes.
- **Speech Bubble & Voice Input:** Windows XP comic-balloon dialogue with typewriter delivery, live URL hyperlinks, action confirmations for critical commands, and speech-to-text mic voice recognition.
- **Desktop Interaction & Memory:** Click and drag Bunbun freely across multi-monitor setups. Bunbun remembers your dragged position on restart, auto-burrows after inactivity, and wakes back up with a click or tray summon.
- **System Tray:** Minimize Bunbun to the tray at any time, toggle visibility, clean your PC with one click, or summon Bunbun back out of his burrow.

### BunbunWORLD Control Center
A complete dashboard styled after vintage Windows XP with bamboo and wood accents:
- **Audio & Media Deck:** Audio visualizer with playlists, lofi tunes, local music streaming, and AI music recommendations.
- **Arcade & Minigames:** Built-in retro arcade featuring Whack-a-Bun 3D, Bun-Sweeper (Minesweeper), Carrot Catch, and Bun-Memory.
- **Wardrobe & Closet:** Dress up Bunbun with equippable hats, glasses, and accessories that render directly on your desktop companion.
- **BunLearn & Preferences:** Configure microphone input devices with live volume meters, manage user profile memory, and customize companion behaviors.
- **Planner & Alarms:** Alarms, countdown timers, reminders, and calendar tasks that alert you even with the dashboard closed.

### Local AI & Assistant
- **Private & Offline:** Local conversational SLM that responds to queries without requiring paid cloud APIs or tracking personal data.
- **App Control & Shortcuts:** Open installed desktop applications, Windows system programs, or custom user shortcuts directly via voice or text.
- **Media Controls:** Manage volume, skip tracks, and play songs from playlists directly through natural chat commands.

### PC Utilities & System Health
- **PC Cleaner:** One-click junk cache clearing, temp directory cleanup, and DNS cache flushing.
- **Process & Bottleneck Inspector:** Monitor high CPU/RAM usage and kill unresponsive tasks with safety confirmation dialogs.
- **Windows Defender:** Trigger security scans directly through native Windows security interfaces.

---

## Requirements

- Windows 10 or Windows 11 (64-bit)

---

## Installation

Download `Bunbun.exe` from the [latest release](https://github.com/itsoulxc/bunbun-companion/releases/latest) and double-click it. No install needed (portable).

---

## Controls

- **Drag:** Click and hold Bunbun to reposition him anywhere on your desktop.
- **Click:** Wake up Bunbun or open his speech bubble to chat.
- **Double-Click:** Launch BunbunWORLD Control Center.
- **Mic Button:** Toggle voice speech-to-text input to talk directly to Bunbun.
- **Right-Click:** Open the context menu for quick PC optimization and shortcuts.
- **System Tray:** Right-click or double-click the tray icon to show, hide, or reset Bunbun's position.

---

## Example Commands

Type or speak commands into Bunbun's speech bubble:

| Command | Action |
|---|---|
| `open [app]` | Launch any installed app or game (e.g., `open chrome`, `open notepad`) |
| `clean pc` / `optimize` | Clean temporary files and free system memory |
| `scan bottlenecks` | Inspect top CPU and memory-consuming processes |
| `kill [process]` | Safely terminate an unresponsive program (with prompt) |
| `play [song]` / `play music` | Play a track or stream music via the media player |
| `volume up` / `volume down` | Adjust media deck playback volume |
| `set an alarm for [time]` | Set a native planner alarm or reminder |
| `tell me a joke` | Hear a fresh joke from Bunbun |
| `tell me a fact` | Share a fun animal or bunny trivia fact |
| `hide` / `burrow` | Send Bunbun into his burrow |

---

## License

Copyright (c) 2026 itsoulxc. All rights reserved.

This software and associated documentation files ("Software") are proprietary.
Unauthorized copying, modification, distribution, reverse engineering, or
commercial exploitation of this software is strictly prohibited without the
express written consent of the copyright owner.
