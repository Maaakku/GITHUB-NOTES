✏️ Your work (from scratch or local repo)

git init                     # Start tracking your project
git add .                    # Stage your updates (like saving a draft)
git commit -m "message"      # Confirm and save a version with a note
git push                     # Push changes to GitHub


🔄 Cloning a teammate’s work (get a copy of a remote project)

git clone https://github.com/username/repo-name.git  # Download repo to your computer
cd repo-name                                         # Enter the project folder


🔃 Pull from GitHub (Sync with remote changes)

git fetch origin main        # Get the latest code from GitHub but don’t merge yet
git pull origin main         # Fetch AND merge changes into your local main branch


🔍 Check their work (what changed in GitHub vs yours)

git diff origin/main         # Show the difference between your local code and GitHub's main


🧪 Update code from your machine to GitHub

git pull origin main         # Update your local repo with the latest from GitHub


🌿 BRANCH COMMANDS (Working on features without affecting main code)

git branch branch-name                       # Create a new branch (doesn't switch yet)
git checkout branch-name                     # Switch to the new branch
git merge feature/login-page                 # Merge the "feature/login-page" branch into the current one
git push origin main                         # Push the merged changes to GitHub’s main branch
