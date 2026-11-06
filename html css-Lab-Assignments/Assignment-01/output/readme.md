Aim

Start a Git repository for the lab folder and save work using commits.

Tasks Performed

Created a folder named html-lab.

Initialized a Git repository using git init.

Configured username and email using git config --local.

Created an index.html file with an H1 heading.

Checked repository status using git status.

Added and committed the HTML file using git add and git commit.

Added an H2 heading and created another commit.

Viewed commit history using git log --oneline.

Git Commands Used

git init

git config --local user.name "Ashish Prajapati"
git config --local user.email "your-email@example.com"

git config user.name
git config user.email

git status
git add index.html
git commit -m "Add home page"

git add index.html
git commit -m "Add next meeting heading"

git log --oneline

HTML Code

<!DOCTYPE html>
<html>
<head>
    <title>My First Page</title>
</head>
<body>
    <h1>Welcome to My HTML Lab</h1>
    <h2>Next Meeting</h2>
</body>
</html>

Expected Output

Git repository initialized successfully.

Username and email displayed in the terminal.

HTML file added and committed successfully.

Two commits displayed in Git history.
