# change directory to your project folder on your Desktop
cd ~/Desktop                       # macOS / Linux
# on Windows Git Bash the Desktop path might be:
# cd /c/Users/<YourWindowsUser>/Desktop

cd "Keerthanya"           # the folder containing your HTML/CSS project

# initialize a git repo
git init

# add all files
git add .

# make the first commit
git commit -m "Initial commit: resume portfolio"

# set main branch (some systems default to main)
git branch -M main

# add the remote (replace URL with the one from GitHub)
git remote add origin https://github.com/<your-username>/<repo-name>.git

# push to GitHub
git push -u origin main
# Resume-
