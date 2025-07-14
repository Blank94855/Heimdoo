  <p align="center">
  <img src="![4841](https://github.com/user-attachments/assets/13242a02-ca96-4299-ad90-0e531ff7ec03)
" width="128" alt="Heimdoo logo">
</p>



# Heimdoo


Heimdoo is an Samsung flashing tool that provides a command-line interface for flashing firmware and system images on supported devices using the Heimdall tool.

---

## Overview

Heimdoo wraps the Heimdall command-line flashing utility into a mobile app environment, allowing users to execute flash commands directly on their device without needing a PC. It is designed for users comfortable with command-line interfaces and manual input of commands.

***An OTG cable or a charger with type C on both sides is required***
---

## Features

- Execute Heimdall flash commands directly from your device 
- Supports flashing multiple partitions and firmware files  
- View device partition information and status  
- Command-line input interface for advanced control  
- Displays output and logs of executed commands  
- Suitable for users with experience in command-line flashing

---

## User Interface

Heimdoo does **not** use graphical buttons or menus. Instead, it provides a terminal-like command-line interface where users manually input commands. Key interface elements:

- **Command Input**: A prompt where you type Heimdall or related commands  
- **Command Output**: Real-time display of command results, errors, and logs  
- **History**: Scrollable history of entered commands and their outputs  
- **File Browser**: Used to select image files or firmware paths when required by commands  
- **Permission Requests**: Prompts for root access or storage permissions when needed

---

## Installation

1. Download the Heimdoo APK file.  
2. Enable installation from unknown sources on your Android device (Settings > Security).  
3. Install the APK and open the app.  
4. Grant any necessary permissions requested (storage access).  
5. Note that you might get a Google play warning, this is because the app is new.
---

## Usage Guide

1. Open Heimdoo to access the command prompt.  
2. Boot your device in download mode. 
3. Manually type flash commands following Heimdall syntax (e.g., `heimdoo flash --boot magisk_patched_boot.img`).  
4. Use the file browser to locate and reference image files in your commands.  
5. Press enter to execute the command and watch the output live.  
6. Review the logs and ensure commands complete without errors.  
7. Reboot your device manually after flashing.

For a detailed info use "help" 
---

## Important Notes

- Heimdoo requires familiarity with Heimdall commands and flashing procedures.  
- Incorrect commands can brick your device; proceed carefully.  
- Not all devices and firmware are supported, particularly newer Samsung models.  
- Always backup before flashing.  
- Use at your own risk.

---

## Credits

- Original Heimdoo app by Rohit Verma (https://github.com/rohitverma882/heimdoo)  
- Fork maintained by blank9485

---

## License

Follows the original Heimdoo licensing terms (idk what it had cuz repo got deleted lol? 

---

## Support

Report issues or request help via the GitHub repository or contact the maintainer.

---

Thank you for using Heimdoo!
