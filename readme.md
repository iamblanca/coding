## Git Basic Commands

### Clone the Repository
Clone the remote repository to your local machine (one-time setup):

```sh
git clone <repo-url>
```

Move into the cloned project folder:
```sh
cd <project-folder>
```

Commit and Push Code
After making changes to the code, use the following commands to push them to the remote repository:

```sh
git add .
git commit -m "your commit message"
git push origin main
# or
git push origin master
```