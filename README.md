# limbo-godot-linux

Godot 4 implementation of Geometry Dash Limbo keys minigame with **Linux support**.

This is a fork of [etherealxx/limbo-godot](https://github.com/etherealxx/limbo-godot) with fixes to make the game run properly on Linux (especially the ending screen).

---

## Features
- Native Linux build (x86_64)
- Also works on Windows
- Same gameplay as the original

---

## How to play on Linux

1. Download the latest release
2. Make the file executable:
   ```bash
   chmod +x limbo_keygen_linux.x86_64
   ```
3. Run the game:
   ```bash
   ./limbo_keygen_linux.x86_64
   ```

---

## For Godot Users

- Clone this repo locally
- Open the project with **Godot 4.7**
- Open the main scene: `res://scenes/main.tscn`

---

## Player Tips

- When all 8 keys are shown (before shuffling), double right-click any key to open the settings menu.
- Useful settings:
  - `transparent_background` → disable for better performance
  - `music_volume`
  - `no_ending_screen`
  - `fullscreen_ending`

- Press **Esc** during the bluescreen to quit instantly.

---

## Credits

- Original project by [etherealxx](https://github.com/etherealxx)
- Linux fixes by TheCookieGod64

---

## License

MIT License
