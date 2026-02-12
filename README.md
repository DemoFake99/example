Practical 2 : 

Create a Repository 

Steps to Create a GitHub Repository
1. Log in to GitHub
•	Go to github.com and sign in with your account.

2. Create a New Repository
•	Click the “+” icon in the top right → select “New repository”.
•	Fill in details: 
o	Repository name (e.g., example)
o	Description (optional)
o	Choose Public or Private
o	Optionally, add a README, .gitignore, or license.
 
Clone Repository 
Steps to Clone a GitHub Repo
1. Copy the Repository URL
•	Go to the repository page on GitHub.
•	Click the green “Code” button.
•	Copy the URL: 
o	HTTPS: https://github.com/username/repo-name.git
o	or SSH: git@github.com:username/repo-name.git (requires SSH setup)
 
2. Open Your Terminal / Command Prompt
•	Navigate to the folder where you want the repo to be cloned: 
•	cd path/to/your/folder
 
3. Run the Clone Command
•	Use the copied URL: 
•	git clone https://github.com/username/repo-name.git
•	This creates a new folder named repo-name with all files and Git history.
 
4. Navigate into the Repo
cd repo-name

5. Verify the Remote
•	Check that the repo is linked correctly: 
•	git remote -v
•	You should see the GitHub URL listed for origin.
 
Add a file 
1. Create or Add a File
•	Create a new file (example: hello.txt): 
•	echo "Hello Git!" > hello.txt
•	Or copy an existing file into the folder.
2. Stage the File
Tell Git to track the file:
git add hello.txt
•	To add all files at once: 
•	git add *
Commit the File
Save the snapshot in Git:
git commit -m "Add hello.txt file"
5. Push to GitHub
Send the changes to your remote repository:
git push origin main
