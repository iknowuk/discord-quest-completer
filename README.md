# Discord Quest Completer

Automatically completes active Discord quests using a script injected via the Developer Console on the Discord Windows desktop app.

## ⚠️ Disclaimer

This uses internal and undocumented Discord APIs. It may break after updates. Use at your own risk. This is for educational and personal use only. I am not responsible for any account actions taken against you.

## Requirements

- Discord Desktop App for **Windows**
- At least one active, uncompleted quest

## How to Use

1. Open the Discord desktop application on Windows.

2. Starts all quests u want complete

3. Press `Ctrl + Shift + I` to open Developer Tools.

4. Click on the **Console** tab.

5. Type `allow pasting` for allow paste the script.

6. Copy the entire content of `script.txt` and paste it into the console.

7. Press `Enter` to run the script.

8. Watch the console log — it will process all your active quests automatically.

9. Close Developer Tools once done.

## Supported Task Types

- `WATCH_VIDEO`
- `WATCH_VIDEO_ON_MOBILE`
- `PLAY_ON_DESKTOP`
- `STREAM_ON_DESKTOP`
- `PLAY_ACTIVITY`

## How It Works

It hooks into Discord's internal modules using `webpackChunkdiscord_app` and simulates quest progress by sending API requests to Discord's own endpoints. No external files or downloads are used.

## Notes

- The script does not store or send your data anywhere.
- It only works on the desktop app, not the browser version.
- If no active quests are found, it will show a message and stop.

## Credits

I am not the creator of the script, I am only sharing it because it worked for me.. Not affiliated with Discord.

## Contact

Discord: iku.uk
