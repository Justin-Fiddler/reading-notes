# Revisions and the Cloud

## Notes

### What is Git?

Git is a DVCS (Distributed Version Control System) that stores snapshots (commits). Git has several key components:

- Git allows users to work locally on a computer that may not even be connected to the internet
- It can track every single change made to a file or directory, and can detect corruption or loss of information in transit.

Files in Git are always in one of three states:

1. Modified - changed but not committed
2. committed - snaphots all tracked files in working directory
3. staged - Ready for commit

### ACP

ACP or add, commit, push is an order of operations for the git to upload to the Git repository.

- Add or "track" files by using `git add file.md` or `git add *`will bring the modified file or files to the staging area
- commit with `git commit file.md`. this command commits a snapshoit of all modifications to tracked files in repository.
- Push with `git push origin main` to finalize the changes to the selected repository. 
- By using `git status`, the user can see exactly what files are modified, staged, and ready for commit

## Answers

1. A sytem that keeps snapshots of all changes made to the file or project. It allows the user to revisit previous versions of the file or project.
2. `Cloning` is copying all files from a repository to a local computer.
3. To track and stage files, a user can either enter each file individually with `git add file.md` or multiple with `git add *`
4. to take a snapshot of your changed files, you'll enter `git commit file.md` for individual files or `git commit -a` for multiple files.
5. to send files to GitHub, a user will need to use command `git push origin main`
