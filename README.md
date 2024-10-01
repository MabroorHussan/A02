# A02

## PART 1: Directions on Using VS Code

### Downloading VS Code

1. Go to the official VS Code website: https://code.visualstudio.com/.
2. Download and install the version suited for your operating system (Windows, macOS, or Linux).
3. Once the installation is complete, launch VS Code.

### Insalling Extensions

1. Click on the Extensions icon in the Activity Bar or press Ctrl+Shift+X
2. Search for the extension you need and click Install. Some popular extensions:
    - Python: Tools for Python development.
    - Prettier: Automatic code formatting.
    - ESLint: JavaScript/TypeScript linting.
    - Markdown All in One: Adds additional Markdown editing features.
    - Live Server: Opens HTML files in your web browser.

### Coding

- New File: Create a new file with *File > New File*.
- Write Code or Text: Start typing your code or content in the editor. VS Code supports syntax highlighting for a wide range of languages such as JavaScript, Python, HTML, and Markdown.
- Tabs: Open multiple files, each file will appear as a tab at the top of the editor
- Open a Folder: *Go to File > Open Folder...* to open a project directory.
- Open a File: Alternatively, open individual files by selecting File > Open File....
- Manual Save: Press Ctrl+S or go to *File > Save*.
- Auto-Save: Enable auto-save by checking *File > Auto Save* to automatically save your work after changes.

### Useful Shortcuts

- Command Palette (Ctrl+Shift+P): Access all commands and actions via this powerful search tool.
- Quick Open (Ctrl+P): Quickly open any file in your workspace.
- Comment/Uncomment Code (Ctrl+/): Toggle comments on lines of code.
- Duplicate Code to Next Line (Alt + Shift + Down): Duplicates the current line of code down to the next line.

## PART 2: Glossary to include these terms in a bulleted list.

- **Branch**: A separate line of development in a Git repository, used to work on new features or bug fixes independently of the main codebase.
- **Clone**: A copy of a Git repository that is downloaded from a remote server to your local machine.
- **Commit**: A record of changes made to the repository, often accompanied by a message describing what was changed.
- **Fetch**: A command used to download updates from a remote repository without merging the changes into your local branch.
- **GIT**: A distributed version control system used to track changes in source code during software development.
- **Github**: A web-based platform for hosting Git repositories and collaborating on code.
- **Merge**: The process of integrating changes from one branch into another.
- **Merge Conflict**: A situation that occurs when two branches have made conflicting changes to the same part of the code, and Git cannot automatically reconcile the differences.
- **Push**: A command that uploads your local repository changes to a remote repository.
- **Pull**: A command that fetches and merges changes from a remote repository into your local repository.
- **Remote**: A version of the repository that is hosted on a server, typically used to collaborate with others.
- **Repository**: A storage location for software packages, code, and related files.

## Github and Git Tutorial

1. Install Git
    - Windows/Mac: Download and install Git from git-scm.com.
    - Linux: Install Git using your package manager (e.g., sudo apt install git).

2. Open Git Bash and Configure Git
    - git config --global user.name "Your Name"
    - git config --global user.email "your.email@example.com"

3. Set Up a GitHub Account
    - Go to GitHub and sign up for an account if you don’t have one. You’ll use this account to store and share your Git repositories.

4. Create a Repository on GitHub
    - Go to GitHub and click the + icon in the top-right corner, then select New repository.
    - Fill in the repository name, description, and choose whether to make it public or private. Optionally, you can add a README file.
    - Click Create repository.

5. Clone the Repository
    - Copy the repository URL from GitHub (it will look something like https://github.com/username/repository.git).
    - Run the following command in your Git Bash terminal: git clone https://github.com/username/repository.git

6. Make Changes and Commit
    - Open the project folder and make changes to files (e.g., edit code or add a new file).
    - Check the status of your changes using: git status
    - Stage the changes (prepare them to be committed): git add .
    - Commit the changes with a message describing what you did: git commit -m "Your commit message"
    - Push the committed changes to the remote repository: git push origin main
    - If you want to get the latest updates from the remote repository (e.g., if someone else has made changes), use the git pull command: git pull origin main


