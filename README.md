# Customizing Windows Terminal for a Beautiful and Efficient Experience

This guide will help you customize your Windows Terminal to enhance its aesthetics and functionality. We'll cover setting up custom backgrounds with light opacity, using retro fonts, choosing attractive color schemes, and efficiently managing panes.

## Getting Started

1. **Install Windows Terminal:**
   If you don't have Windows Terminal installed, you can download it from the Microsoft Store or from the [official repository](https://github.com/microsoft/terminal).
   > **Note:** After installing windows terminal please make it as a default terminal.

2. **Install Git-Bash:**
   If you don't have Git-Bash installed, you can download it from [official repository](https://gitforwindows.org/). 

3. **Clone this Repository and setup:**
   Clone or download this repository to get access to the custom settings and configurations we'll use.

   - `git clone git@github.com:yebh17/windows-terminal.git`
   - `cd windows-terminal`

   Open your command prompt and run the following commands
   - `move C:\\Users\\%USERNAME%\\AppData\\Local\\Packages\\Microsoft.WindowsTerminal_8wekyb3d8bbwe\\LocalState\\settings.json C:\\Users\\%USERNAME%\\AppData\\Local\\Packages\\Microsoft.WindowsTerminal_8wekyb3d8bbwe\\LocalState\\settings_original.json`

   We backup the original settings.json file and replace it with my custom settings.json file
   - `copy settings.json C:\\Users\\%USERNAME%\\AppData\\Local\\Packages\\Microsoft.WindowsTerminal_8wekyb3d8bbwe\\LocalState\\`
   - `copy media C:\\Users\\%USERNAME%\\AppData\\Local\\Packages\\Microsoft.WindowsTerminal_8wekyb3d8bbwe\\LocalState\\`

   Now close the command prompt and type 'terminal' in 'start' and open it.

   Voila!! You're up and running...

4. **Import Custom Settings:**
   You can now change this `settings.json` file in `C:\\Users\\%USERNAME%\\AppData\\Local\\\\Packages\\Microsoft.WindowsTerminal_8wekyb3d8bbwe\\LocalState\\settings.json` as per your preferences.

   You can check this official documentation for more details. [windows-terminal-documentation](https://learn.microsoft.com/en-us/windows/terminal/)