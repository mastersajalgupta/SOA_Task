# SOA Internship Program

# Assignment – Git + Linux CLI Hands-on

Duration: 90–120 mins

Submission:
Share:

1. Raise a PR with your branch
2. Final README.md

Rules:

* Use terminal only
* Do not use file explorer
* Commit after every section
* Follow steps sequentially

---

# PART 1 — Linux Navigation & File Management

## Task 1 — Create Workspace

Create a folder:

internship-assignment


Move into it.
Commands to use:

mkdir
cd
pwd


---

## Task 2 — Create Project Structure

Create this structure:

text
internship-assignment
│
├── docs
├── scripts
├── logs
├── images
└── notes


Commands:

mkdir
ls


---

## Task 3 — Create Files

Create:

text
docs/git.txt
docs/linux.txt
notes/commands.txt
scripts/start.sh
logs/app.log


Commands:

touch
ls


---

## Task 4 — Add Content

Inside:
git.txt

Write:

text
1. What is Git
2. Why Git is useful
3. Difference between Git and GitHub


Inside:
linux.txt

Write:

text
1. What is Linux
2. Three commands learned

---

## Task 5 — Linux Search

Search:

text
Git

inside all files.

Commands:

grep
find


# PART 2 — Git Fundamentals

## Task 6 — Initialize Repository

Inside project:

Initialize Git.

Commands:


git init
git status


---

## Task 7 — First Commit

Stage all files.

Commit:

text
Initial Project Setup


Commands:


git add .
git commit



## Task 8 — Track Changes

Modify:

text
docs/git.txt


Add:

text
Three git commands learned


Check changes.

Commands:


git status
git diff


Commit.

Message:

text
Updated git notes


---

## Task 9 — Branching

Create branch:

text
feature/<your-name>


Example:


git checkout -b feature/rahul


Verify:


git branch


Deliverable:
Screenshot.

---

## Task 10 — Feature Development

Inside branch:

Create:

text
notes/learning.md


Write:

text
My top 5 learnings


Commit:

text
Added learning summary


---

## Task 11 — Merge Branch

Switch:

text
main


Merge:

text
feature/<your-name>


Commands:


git checkout main
git merge



---

# PART 3 — GitHub

## Task 12 — Create GitHub Repository

Move to your original branch, publish your branch.
and then push the changes using 

git push origin feature/<your-name>

Create Pull Request.

Configuration:

Source:

feature/<your-name>

Destination:

main

PR Title:

Submission – <your-name>

Description:

Completed all assignment tasks.

Topics practiced:
- Linux Commands
- Git Workflow
- Branching
- Merge
- GitHub

Task 13 : Review Feedback

If changes are requested:

Update code.

Commit.

Push again:

git add .
git commit -m "Resolved review comments"
git push

PR updates automatically.