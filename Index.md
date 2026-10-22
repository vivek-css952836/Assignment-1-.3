Step-1 & 2: Create Folders and Files
Option A: macOS / Linux (Bash/Zsh)
Bash
# 1. Create the main project folder and navigate into it
mkdir web-development-practice
cd web-development-practice

# 2. Create the week folders
mkdir week-1 week-2 week-3

# 3. Create an index.html file inside each week folder
touch week-1/index.html week-2/index.html week-3/index.html
Option B: Windows (PowerShell)
PowerShell
# 1. Create the main project folder and navigate into it
mkdir web-development-practice
cd web-development-practice

# 2. Create the week folders
mkdir week-1, week-2, week-3

# 3. Create an index.html file inside each week folder
New-Item -ItemType File week-1/index.html
New-Item -ItemType File week-2/index.html
New-Item -ItemType File week-3/index.html
Step-3: Practice Navigation, Renaming, and Deleting
To fulfill the practice requirement, run these quick commands in your terminal while inside your project folder:

Navigate into a folder:

Mac/Linux/Windows: cd week-1

Go back to the parent folder:

Mac/Linux/Windows: cd ..

Rename a folder:

Mac/Linux: mv week-3 week-three (then change it back: mv week-three week-3)

Windows (PowerShell): Rename-Item week-3 week-three (then change it back: Rename-Item week-three week-3)

Delete/Remove a test folder:

Mac/Linux: mkdir temp && rmdir temp

Windows (PowerShell): mkdir temp; Remove-Item temp

Step-4: Open in VS Code
Once you are inside the web-development-practice directory, open the entire project in Visual Studio Code with a single command:

Bash
code .
(Note: If the code command gives an error, open VS Code manually, press Ctrl+Shift+P / Cmd+Shift+P, type Shell Command: Install 'code' command in PATH, press Enter, and try again).

Final Folder Structure Preview
Your final project tree will look like this:

Plaintext
web-development-practice/
├── week-1/
│   └── index.html
├── week-2/
│   └── index.html
└── week-3/
    └── index.html
To complete your assignment submission, simply copy the terminal command history you used and take a screenshot of your VS Code sidebar showing this folder structure.