# Vendex
# Navigate to your project folder
cd /path/to/your/vendex_project

# Initialize a Git repository (if not already done)
git init

# Add all your project files
git add .

# Commit the files with a message
git commit -m "Initial commit for Vendex project"

# Rename the default branch to main (if not already main)
git branch -M main

# Add your GitHub repository as the remote origin (replace <yourusername> with your GitHub username)
git remote add origin https://github.com/<yourusername>/vendex.git

# Push your files to GitHub
git push -u origin main
