# windows-terminal-all-commands
may this commands help you to learn and survive in future


🔹 CMD (Command Prompt)

dir             :: List files and folders
cd              :: Change directory
copy            :: Copy files
del             :: Delete files
cls             :: Clear the screen
echo            :: Print text
set             :: Set environment variables
tasklist        :: List running processes
shutdown /s     :: Shutdown the PC
ipconfig        :: Network config info


🔹 PowerShell

Get-Process                  :: List running processes
Get-ChildItem                :: List directory contents (like `ls`)
Set-Location                 :: Change directory (like `cd`)
Copy-Item                    :: Copy files
Remove-Item                  :: Delete files
Get-Content filename.txt     :: View contents of file
Start-Process appname        :: Launch apps
Get-Help                     :: Get help on commands


🔹 WSL (Windows Subsystem for Linux)

ls           # List directory
cd           # Change directory
cp           # Copy
mv           # Move/rename
rm           # Delete
nano         # Text editor
sudo apt update && sudo apt upgrade  # Update packages


Launch WSL with:
powershell()


wsl           # Launch default distro
wsl -l -v     # List installed WSL distros


🔹 Azure Cloud Shell

Access via a profile in Terminal if configured:
powershell>>>


az login      # Sign in to Azure
az vm list    # List VMs



⚙️ Settings and Customization
Open Settings:
Via dropdown → "Settings" or press Ctrl + ,



JSON Settings File:

You can directly edit the settings JSON for advanced customization.
Key areas:

json


{
  "profiles": {
    "list": [
      {
        "name": "Ubuntu",
        "commandline": "wsl.exe -d Ubuntu",
        "colorScheme": "Campbell",
        "fontFace": "Cascadia Code",
        "icon": "ubuntu.png"
      }
    ]
  },
  "schemes": [
    {
      "name": "MyTheme",
      "background": "#0C0C0C",
      "foreground": "#CCCCCC",
      ...
    }
  ],
  "keybindings": [
    {
      "command": "newTab",
      "keys": ["ctrl+t"]
    }
  ]
}



🧭 Useful Windows Terminal Commands
Command	Action>>>


wt	Launch Windows Terminal
wt -p "Command Prompt"	Open specific profile
wt -w 0 nt -p "PowerShell"	New tab in existing window
wt -d .	Open Terminal in current directory


⌨️ Common Keyboard Shortcuts
Shortcut	Action>>>


Ctrl + Shift + T	New tab
Alt + Shift + D	Split pane
Ctrl + ,	Open settings
Ctrl + Shift + W	Close tab
Ctrl + Shift + F	Find
Ctrl + Shift + C	Copy
Ctrl + Shift + V	Paste



🔄 Tips and Tricks


Use Cascadia Code font for ligature support.
Customize color schemes for better visibility.
Use aliases in PowerShell or WSL for custom shortcuts.
Install Oh My Posh for prompt themes in PowerShell or WSL.


thank you for everything A.M.
