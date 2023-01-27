# Prerequisites  
Before Installing and Configuring Starship you need some NerdFonts!

## Fonts
[NerdFonts Homepage](https://www.nerdfonts.com/font-downloads)  
I am using [JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/JetBrainsMono.zip)

## CMD
[Clink](https://github.com/chrisant996/clink) combines the native Windows shell cmd.exe with the powerful command line editing features of the GNU Readline library, which provides rich completion, history, and line-editing capabilities. 


# Installation Starship
* Go to https://starship.rs/ and download starship for our os.  (Repeat in WSL)

* Install starship.toml file. 
In windows and linux create `.config` folder in your home folder and save `starship.toml` file.

* Configure Shell

### Powershell
Open a powershell shell and type "code $PROFILE" or "notepad $PROFILE". 
See sample "Microsoft.PowerShell_profile.ps1"

### zsh
Open .zshrc (in your home folder) and modify see sample .zshrc
Copy folder .zsh from to your home folder.

### CMD
Place `starship.lua` in `c:\Program Files (x86)\clink\`

# Installation Windows Terminal 
Install from [Microsoft Store](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701?hl=sv-se&gl=se) or [Github](https://github.com/microsoft/terminal/releases).

## Configure Windows Terminal 

* Add Color Schema for Windows Terminal's Json file.

Section "schemes"
```
{
            "background": "#1A1A1A",
            "black": "#121212",
            "blue": "#2B4FFF",
            "brightBlack": "#666666",
            "brightBlue": "#5C78FF",
            "brightCyan": "#5AC8FF",
            "brightGreen": "#905AFF",
            "brightPurple": "#5EA2FF",
            "brightRed": "#BA5AFF",
            "brightWhite": "#FFFFFF",
            "brightYellow": "#685AFF",
            "cursorColor": "#FFFFFF",
            "cyan": "#28B9FF",
            "foreground": "#F1F1F1",
            "green": "#7129FF",
            "name": "Custom_Schema",
            "purple": "#2883FF",
            "red": "#A52AFF",
            "selectionBackground": "#FFFFFF",
            "white": "#F1F1F1",
            "yellow": "#3D2AFF"
        }
```

* Modify Profiles Appearance.  
* Change Color schema to "Custom_Schema"  
* Change Font Face to "JetBrainsMono Nerd Font"  



