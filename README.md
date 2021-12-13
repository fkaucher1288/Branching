## Git Cheat Sheet

### Basic Commands
* 'git init' - Initialize local Git repository
* 'git add .' - Add all files in and under current directory to git index, staging them for commit
* git commit -m "Message" - Commit changes to local repo with commit message "Message"

### Information Commands
* 'git status' - display currrent status of local working directory/respository
* 'git log' - list commit history
* 'git log --online' - list commit history, compact format

### Remote Commands
* 'git remote add irigin remoteURL' - Add alias "origin" for remote repositoryURL "remoteURL"
* 'git push origin main' - Push locally-committed changes to 'main' branch on remote repository
* 'git push -u origin main' - Same, setting "origin main" as default subsequent 'git push'
