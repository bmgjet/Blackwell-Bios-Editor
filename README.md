# Blackwell BIOS Editor

![Blackwell BIOS Editor Screenshot](https://github.com/bmgjet/Blackwell-Bios-Editor/blob/main/5090bbe.png?raw=true)

## Overview
Blackwell BIOS Editor is a tool for modifying the BIOS of NVIDIA GPUs from the Blackwell architecture. This editor allows you to adjust the power limit of your graphics card, enabling better control over performance and efficiency.

## NOTE
This is only for 5090 it may work on others. Its just porting the Ampere bios editors code with Blackwells updated power table addresses. I havnt added the checksum calculation code since theres no point saving files when there is no method to bypass falcon cert check on them during flash. That would lead to this being only being used for fake bioses to upload to TPU and waste every ones time so saving wont be enabled.

## Features
- Modify power limits of NVIDIA Blackwell GPUs
- User-friendly interface for BIOS editing

## Requirements
- Windows 10/11 or Linux (Wine compatibility may vary)
- NVIDIA GPU from the Blackwell series
- Administrator privileges to flash modified BIOS

## Usage
1. Backup your original BIOS using `nvflash` before making any modifications.
2. Open the BIOS file in Blackwell BIOS Editor.
3. Adjust the power limit values as needed.
4. Save the modified BIOS.
5. Flash the modified BIOS using `nvflash`.
6. Reboot your system and verify changes.

## Disclaimer
Modifying your GPU BIOS carries risks, including potential hardware damage and warranty voidance. Use this tool at your own risk. The developer is not responsible for any damage caused by improper usage.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## License
This project is licensed under the [MIT License](LICENSE).

## Credits
Developed by [bmgjet](https://github.com/bmgjet).

