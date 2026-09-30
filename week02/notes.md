pwd shows the path of the current working directory I'm in.
ls -a showed all the files along with hidden files and directories.
The first column seems to represent the file type and permissions.
This works because coding-cafe/week02 is a relative path starting from my current location (the home folder). It looks for the coding-cafe directory inside my current working directory.
mv moved README-backup.md from coding-cafe to week01 and it renamed README-backup.md to old-readme.md
I have 19 folders
/usr/bin/python3
No, he had a different path because his username and folders' names and mine are different.
Shell said "Command not found".This means the shell searched through all the folders listed in my PATH for an executable named pyton3, and couldn't find a match because of the typo.
It did not appear because (.venv) is hidden, and plain ls hides hidden files.
.(venv) appeared at the very beginning of my prompt, indicating that the virtual environment is currently active.
No, it points to the local virtual environment's python instead of the global one. 
certifi, charset-normalizer, idna, requests, urllib3.
It points back to the global system Python path.
ls -h prints file sizes with suffixes like KB, MB, or GB.
Ctrl + C terminates or cancels the current running process/command, whereas Ctrl + D sends an EOF (End-of-File) signal, which exits or closes the current shell session.