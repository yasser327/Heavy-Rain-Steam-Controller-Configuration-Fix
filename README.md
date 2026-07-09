# Heavy Rain: Steam Controller Configuration Fix

This repository provides a fix for the "Load Steam Controller Configuration File Failed" error when trying to play *Heavy Rain* (PC) with a USB Xbox 360 controller.

## The Issue
When launching the game, you might encounter a warning window stating: 
`Load Steam Controller Configuration File Failed. 1. Make sure this account has been registered to controller which you want to use...`

This happens because the default controller configuration file uses incorrect syntax and is missing button mappings (like the "Back" button), preventing the API from properly reading your controller.

## The Solution
Replacing the broken configuration text with the properly formatted variables will bypass the error and allow your controller to work perfectly.

### Installation Instructions
1. Navigate to your *Heavy Rain* installation directory.
2. Locate the `steam_settings` folder (or `steam_settings/controller`).
3. Find the file named `GamepadSetting.txt`. (If it doesn't exist, create it).
4. Open the file, delete any existing text, and paste the entire contents of the `GamepadSetting.txt` file from this repository.
5. Save the file, close it, and launch the game!
