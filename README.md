## Complete Git & GitHub Notes
# What is Git?

Git is a tool that helps you save, track, and manage changes in your project.
Think of it as undo + history + safe backup for your code.

# What is GitHub?

GitHub is a website where you store your Git projects online so your code is safe, shareable, and accessible anywhere.

* Git = tool
* GitHub = website for hosting Git project

## git installation & initalization

1. Install Git

Download Git from google: “Git download”.
Install with default settings.

Check Git installed:
git --version

## 2. Configure Git (One Time Only)
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

## Git Initialization 
git init


## Flow of Git
write --> Add --> Commit --> Push

## Git Workflow 

Here is the step-by-step flow you will follow every time:

--> Initialize a repository
--> Check file status
--> Stage files
--> Commit changes
--> Connect to GitHub
--> Push your code
--> Pull updates
--> Work with branches

## Commands of git

1. Check Status

Shows which files are new, changed, or ready to commit.
git Status

2. Add (Stage) Files
* Add all files   --->    git add .
* Add specific file --->  git add index.html


## Commit (Save Changes)

git commit -m "message about what you changed"
A commit is like a save point.