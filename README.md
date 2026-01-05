# Introduction and Steps

Command++ is a command utility program that upgrades Windows Command Prompt and the new Windows Terminal, The steps to download Command++ are:

1. Download Python if you haven't already *(3.13 is preferred)*
<img width="1360" height="768" alt="Downloading Python - Command++" src="https://github.com/user-attachments/assets/de632b09-471a-4b79-a4c9-d576bc859429" />
👆 This step is very important for running Command++


2. Setup Python.

![Credits to LO4D.com for the image since I can't reinstall Python](https://github.com/user-attachments/assets/f01b0fab-0455-45e3-b7d8-158748a5a8c2)


3. Download the latest release of Command++.
<img width="1360" height="768" alt="Download Command++" src="https://github.com/user-attachments/assets/86a3a69a-d233-4e49-9307-47e827bec9ee" />


4. Unzip the ZIP that you have downloaded.
<img width="1360" height="768" alt="Unzip Command++" src="https://github.com/user-attachments/assets/960f45d4-9f36-4b25-aec3-f74f2f86af7d" />
*(Note: I am using WinRAR but you can use Windows' unzipper to unzip the ZIP, but don't delete any files. They are important.)*


5. Create a folder named "Command++" *(Recommended but you can keep it any name, but it might be already named Command++.)*
<img width="121" height="40" alt="Folders" src="https://github.com/user-attachments/assets/a07c3de3-264b-45d0-9491-49f04c0794dc" />


6. Open Command Prompt or Terminal.
<img width="1360" height="768" alt="Open Terminal" src="https://github.com/user-attachments/assets/4aea9e9d-51a0-4fd1-ac48-c7fecde5b410" />
*(I have opened Terminal, but you can open Command Prompt too.)*


7. Write `cd Command++` in the Terminal/CMD window.
<img width="484" height="123" alt="cd Command++" src="https://github.com/user-attachments/assets/3b2039b6-063f-47d2-8181-59a699e0a081" />


8. Now type `python cmdpp.py` in the Terminal/CMD window.
<img width="454" height="96" alt="cmdpp.py" src="https://github.com/user-attachments/assets/046c9d85-fef1-4b6a-9e67-156745e28829" />


9. Now click the 'Enter' key, you might get a screen like this:
<img width="450" height="222" alt="Command++ image" src="https://github.com/user-attachments/assets/374bbdc1-857e-4ede-b1ed-927c59752061" />


10. Now type `cmdpp help` to view all commands. *(You can also enter normal Windows commands.)*
<img width="1347" height="716" alt="cmdpp help" src="https://github.com/user-attachments/assets/e5af2429-3d0c-490f-81d5-c6dc7d492f46" />

Here's an overview of what each command does:

| Command | What it does |
|---------|--------------|
| `cmdpp help` | Opens the help window |
| `cmdpp fsys` | Fetches system OS and hardware |
| `cmdpp fetch` | Will see if the requested app is downloaded or not |
| `:s` | Shows the history of commands you've entered |
| `cmdpp history show` | Same as `:s` |
| `cmdpp history clear --yes` | Clears your command history |
| `!name` | Runs a snippet (a snippet is a simple way of running commands) |
| `cmdpp snippet add (name) (cmd)` | Adds a new snippet |
| `cmdpp snippet run (name)` | Same as `!name` but is more stable |
| `cmdpp snippet list` | Lists all snippets. |

# Aliases
An 'alias' is a shortcut of some command that's shorter (obviously) and faster. They can be used like `cmdpp commands` -> `cmdpp help` and vice versa.
Here are some aliases:
`cmdpp help` -> `cmdpp commands`
`cmdpp snippet run (name)` -> `!name`
`:saved` -> `:s`




