# Wallpaper Changer
This is a simple Powershell script that pick a random image and apply it as the new Windows wallpaper.

## Install

Clone the repository  
Add your images in ./wallpapers  
Open your task scheduler  
Create a new task :
- Action : Start a programm
- Programm/script : powershell
- Args : absolute path to PowerShell file (example : D:\wallpaper\change-wallpaper.ps1)
- Start in : absolute path to the project folder (example : D:\wallpaper)
- Trigger : As you want (I use : when a user logs in)