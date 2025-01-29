Step 1: Prepare Your Portfolio Folder
Create a Folder on your computer, name it portfolio-website.
Move your website files (like index.html, styles.css, and other assets) into this folder.
Ensure your folder structure looks like this:
Copy
Edit
portfolio-website/
├── index.html
├── styles.css
📌 Step 2: Upload Your Portfolio Files to GitHub
(A) Open Your Local Project Folder in Terminal
Windows Users: Open Git Bash or Command Prompt.
Mac/Linux Users: Open Terminal.
Navigate to your portfolio folder by running the following command:
bash
Copy
Edit
cd path/to/your/portfolio-website
Example (if your folder is on the Desktop):
bash
Copy
Edit
cd Desktop/portfolio-website
(B) Run Git Commands to Upload Files
Initialize Git in Your Project Folder

bash
Copy
Edit
git init
This initializes a Git repository in your folder.

Add All Files to Git Tracking

bash
Copy
Edit
git add .
This tells Git to track all files in the folder (index.html, styles.css, etc.).

Commit Your Changes

bash
Copy
Edit
git commit -m "Initial commit"
This saves your changes locally with the message "Initial commit".

Set the Default Branch to main

bash
Copy
Edit
git branch -M main
GitHub uses main as the default branch, so this command renames it.

📌 Step 3: Create a Repository on GitHub
Go to GitHub.
Click on "New" (or go to Create Repository).
Enter the Repository Name: portfolio.
Set Visibility to Public (so anyone can view your site).
Do NOT check "Initialize with README" (since you already have files).
Click "Create Repository".
📌 Step 4: Connect Your Local Project to GitHub
Now that your repository is created, link it to your local project:

Connect Your Local Folder to the GitHub Repository Run the following command:

bash
Copy
Edit
git remote add origin https://github.com/venkateshmoodu/portfolio.git
This links your local project to the GitHub repository.

Push Your Code to GitHub Upload your portfolio files by running:

bash
Copy
Edit
git push -u origin main
📌 Step 5: Enable GitHub Pages
Go to your GitHub repository → https://github.com/venkateshmoodu/portfolio.
Click on "Settings".
On the left menu, click "Pages".
Under "Branch", select "main".
Click "Save".
📌 Step 6: View Your Live Portfolio
After a few minutes, GitHub will generate a URL for your site.

Your portfolio will be available at:

arduino
Copy
Edit
https://venkateshmoodu.github.io/portfolio/
This is your official portfolio link! 🎉
