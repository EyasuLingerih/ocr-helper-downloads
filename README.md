# OCR Helper — downloads

Optional desktop helper for **Scriptorium**, the scan-to-text web app. It runs text recognition on all of your computer's CPU cores, which makes big documents roughly 3× faster than running inside the browser. The web app finds it automatically.

| Your computer | Download |
|---|---|
| Mac with Apple chip (M1, M2, M3, M4) | [OCR-Helper-mac-arm64.zip](https://github.com/EyasuLingerih/ocr-helper-downloads/releases/latest/download/OCR-Helper-mac-arm64.zip) |
| Mac with Intel chip | [OCR-Helper-mac-x64.zip](https://github.com/EyasuLingerih/ocr-helper-downloads/releases/latest/download/OCR-Helper-mac-x64.zip) |
| Windows 64-bit | [OCR-Helper-win-x64.zip](https://github.com/EyasuLingerih/ocr-helper-downloads/releases/latest/download/OCR-Helper-win-x64.zip) |

Not sure which Mac you have? Apple menu → About This Mac → look for "Chip".

## Use it
1. Unzip and start it: **Start OCR Helper.command** (Mac) or **Start OCR Helper.bat** (Windows).
   - **Mac, first time only:** macOS will say it "could not verify" the file, because the helper is not signed by Apple. Click **Done** (not "Move to Trash"), then open **System Settings → Privacy & Security**, scroll to the bottom, click **Open Anyway** and enter your password. Double-click the file again and choose **Open**. (On older macOS versions, right-click the file → Open → Open also works.)
   - Prefer Terminal? Run `xattr -dr com.apple.quarantine "OCR Helper"` in the folder that contains it, then double-click as normal.
   - **Windows:** if SmartScreen warns, choose **More info → Run anyway**.
2. Leave the window open while you work.
3. Open Scriptorium. It shows "Desktop helper found" and uses it automatically.

## Privacy
The helper only listens on your own computer (127.0.0.1) and only answers the Scriptorium web app. Your documents never leave your computer. Language data is downloaded once on first use and cached in a `.ocr-helper` folder in your home folder.

Nothing is installed: delete the folder to remove it.
