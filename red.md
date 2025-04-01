2. Initialize Git in Your Local Project
Open your terminal (Command Prompt, Git Bash, or Terminal) and navigate to your project folder:

bash
Copy
Edit
cd /path/to/your/local/project
Then, initialize Git:

bash
Copy
Edit
git init
This creates a .git folder, turning the directory into a Git repository.

3. Add and Commit Your Files
Add all files to Git:

bash
Copy
Edit
git add .
Commit the changes:

bash
Copy
Edit
git commit -m "Initial commit"
4. Connect Your Local Repo to GitHub
Add the remote repository URL:

bash
Copy
Edit
git remote add origin https://github.com/your-username/repo-name.git
Verify the remote URL:

bash
Copy
Edit
git remote -v
You should see:

perl
Copy
Edit
origin  https://github.com/your-username/repo-name.git (fetch)
origin  https://github.com/your-username/repo-name.git (push)
5. Push Your Code to GitHub
If this is a new repo, set the default branch to main and push:

bash
Copy
Edit
git branch -M main
git push -u origin main
If you’re using master instead of main, use:

bash
Copy
Edit
git push -u origin master
6. Check Your Repo on GitHub
Go to your GitHub repository, refresh the page, and your project should be there! 🎉

Future Changes? Just Commit and Push!
Once your project is linked to GitHub, you only need to:

bash
Copy
Edit
git add .
git commit -m "Updated files"
git push origin main  # or master
