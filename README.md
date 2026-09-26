# OCR Helper — downloads

Optional desktop helper for the **OCR Document Pipeline** web app. It runs text recognition on all of your computer's CPU cores, which makes big documents roughly 3× faster than running inside the browser. The web app finds it automatically.

| Your computer | Download |
|---|---|
| Mac with Apple chip (M1, M2, M3, M4) | [OCR-Helper-mac-arm64.zip](https://github.com/EyasuLingerih/ocr-helper-downloads/releases/latest/download/OCR-Helper-mac-arm64.zip) |
| Mac with Intel chip | [OCR-Helper-mac-x64.zip](https://github.com/EyasuLingerih/ocr-helper-downloads/releases/latest/download/OCR-Helper-mac-x64.zip) |
| Windows 64-bit | [OCR-Helper-win-x64.zip](https://github.com/EyasuLingerih/ocr-helper-downloads/releases/latest/download/OCR-Helper-win-x64.zip) |

Not sure which Mac you have? Apple menu → About This Mac → look for "Chip".

## Use it
1. Unzip and start it: **Start OCR Helper.command** (Mac) or **Start OCR Helper.bat** (Windows).
   - Mac, first time only: right-click the file → Open → Open (the app is not signed by Apple).
   - Windows: if SmartScreen warns, choose More info → Run anyway.
2. Leave the window open while you work.
3. Open the web app. It shows "Desktop helper found" and uses it automatically.

## Privacy
The helper only listens on your own computer (127.0.0.1) and only answers the OCR web app. Your documents never leave your computer. Language data is downloaded once on first use and cached in a `.ocr-helper` folder in your home folder.

Nothing is installed: delete the folder to remove it.
