# QuickFolders-ContextMenu PowerShell Script

## Description
QuickFolders-ContextMenu is a PowerShell script designed to enhance your Windows desktop experience. It adds a dynamic submenu to your desktop context menu, providing quick and easy access to all folders located on your desktop. Easily add or remove this feature with administrative privileges. This script is ideal for users seeking to streamline their navigation and improve desktop organization.

## Compatibility
- **Windows 11**: Fully compatible with native PowerShell 5.1. Tested and functional on the latest version of Windows.
- **Windows 10**: Fully compatible with native PowerShell 5.1.
- **Windows 8/8.1**: Compatible, especially with PowerShell updated to the latest version.
- **Windows 7**: Compatible, but requires manual update to PowerShell 5.1.
- **Note**: Not recommended for Windows Vista or XP due to lack of support and potential security risks.

## Prerequisites
- Administrative privileges are required to run this script.
- PowerShell 5.1 or later.

## Installation
1. **Download the Script**:
   - Download `QuickFoldersContextMenu.ps1` from this repository.

2. **Creating a Shortcut**:
   - Right-click on the downloaded `.ps1` file.
   - Select `Send to` > `Desktop (create shortcut)`.
   - Right-click on the shortcut created on the desktop and select `Properties`.
   - In the `Target` field, prepend the existing path with `powershell.exe -ExecutionPolicy Bypass -File `. It should look like this: `powershell.exe -ExecutionPolicy Bypass -File "path\to\your\QuickFoldersContextMenu.ps1"`.
   - Click `OK` to save the changes.

## Usage
1. **Run as Administrator**:
   - Right-click on the shortcut you created.
   - Select `Run as Administrator`.

2. **Follow the Prompts**:
   - The script will prompt you to either Add (A) or Remove (R) the QuickFolders option.
   - Type `A` to add the QuickFolders to your context menu.
   - Type `R` to remove it.

## Contributing
Contributions to the QuickFolders-ContextMenu script are welcome. Please feel free to fork the repository, make changes, and submit pull requests.

## License
This project is licensed under MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer
This script modifies the Windows Registry. While it has been tested and is expected to work as intended, users should use it at their own risk. Always ensure you have backups of important data before making changes to the system registry.
