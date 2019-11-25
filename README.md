# windows-terminal-settings

Sharing profile settings for Windows Termial between different machines is very easy:
1. Create a git repository in the folder where **profile.json** is (in my case under     _"C:\Users\<user>\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\profiles.json"_)

2. Create git repo on GitHub

3. Make sure to set VS Code as default editor for **json** files

4. Every time you change settings in **profile.json**, simply commit the changes to git repo and pull if you are on another machine.
