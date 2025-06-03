# Powershell Profiles
This is a collection of my personal powershell profiles, some are for fun others have an actual funcunality
## Installation and Usage
To get this up and running type:
```bash
winget install --id Microsoft.PowerShell --source winget
```
To launch the correct terminal type: ```
pwsh.exe```, instead of ```powershell.exe```

Edit the profile by typing
```bash
nano $PROFILE
```

Paste your desired code into it, i.e. kys.ps1 or fullprofile.ps1

## Available Functions


| Function   | Description                                                                          | Parameters                                  |
|------------|--------------------------------------------------------------------------------------|---------------------------------------------|
| kys        | Displays an image of LowTierGod and closes the terminal, you can replace it with something else if you want.                             | None                                        |
| rick       | Sends you to the "Never Gonna Give You Up" YouTube video also known as a "Rick Roll".            | None                                        |
| flash      | Flashes the terminal screen between black and white.                                   | None                                        |
| flash+     | Continuously flashes the terminal screen through a sequence of different colors.       | None                                        |
| spin       | Shows a simple loading spinner animation in the console.                               | None                                        |
| beep       | Plays a random number of beeps with random frequencies and durations.                  | None                                        |
| beep-morse | Beeps out a user-defined message in Morse code.                                      | `-message <string>` (Mandatory)             |


## Future Development
I plan to add a parameter for speed in beep-morse and more functions