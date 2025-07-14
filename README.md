   ![4841](https://github.com/user-attachments/assets/d10490e1-593a-47d3-982e-8dfbc7a5de48)



# Heimdoo


Heimdoo is an Samsung flashing tool that provides a command-line interface for flashing firmware and system images on supported devices using the Heimdall tool.
![4842](https://github.com/user-attachments/assets/fe987924-45f3-4011-8d12-311e052682a1)


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
```
⚠️ WARNING ⚠️

This software is provided “as is” without warranty of any kind, either expressed or implied. 
By using this application, you acknowledge that you are doing so at your own risk.

Flashing firmware or modifying system images carries an inherent risk of permanently 
damaging or bricking your device. This tool is intended for users who understand the 
implications of system-level changes on Android devices. Improper use can lead to data 
loss, device malfunction, or render the device unusable.

The developer of this fork and the original Heimdoo developer shall not be held responsible 
for any damage, loss of data, hardware failure, voided warranties, or any other consequences 
that may occur through the use or misuse of this application.

By proceeding to use this app, you agree to take full responsibility for any outcomes that 
result from its usage.

DO NOT use Heimdoo unless you understand what you're doing. 
Always back up your data and proceed with extreme caution.
```





Thank you for using Heimdoo!
Support server: https://discord.gg/daNdzVMw 
