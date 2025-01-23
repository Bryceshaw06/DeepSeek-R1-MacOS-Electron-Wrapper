<div align="center">
  <h1 style="font-size: 48px; font-weight: bold;">DeepSeek-R1 MacOS Application</h1>
</div>


<p align="center">
  <img src="https://github.com/user-attachments/assets/92103f05-8b12-40ae-8243-60ff094363fb" width="80%" />
</p>



The **DeepSeek-R1 MacOS Application** is just an Electron wrapper for the website. I prefer using a dedicated app for sites like this, as it’s much easier to manage compared to having everything scattered across multiple browser tabs. In my experience, browser shortcut apps often cause issues too, so this application provides a more seamless experience.

## Installation Instructions

1. **Download** the app from the [**Releases**](https://github.com/Bryceshaw06/DeepSeek-R1-MacOS-Electron-Wrapper/releases) tab. (x64 for Intel Macs, ARM64 for M-Series Macs)
2. **Extract** the `.zip` file after downloading.
3. **Move** the `.app` file to your **Applications** folder.
4. **Run** the app. If you encounter a security warning preventing the app from opening, you can bypass this by following these steps:
   - Open **System Preferences**.
   - Navigate to the **Privacy & Security** section.
   - At the bottom of the page, you’ll see an option to allow the app to open. Click **Allow**.

Alternatively, if the app still won’t open, you can run the following command in the terminal to remove the quarantine attribute:

   ```
   sudo xattr -rd com.apple.quarantine /Applications/DeepSeek-R1.app 
  ```
(But note this isn't general good practice)

## Issues?

If you have any issues or find any problems, feel free to open an issue under the [**Issues Tab**](https://github.com/Bryceshaw06/DeepSeek-R1-MacOS-Electron-Wrapper/issues) 
