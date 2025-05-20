git init - initialize a new git repository
git config --global user.name - set your global git user name
git config --global user.email - set your global git user email
git branch - list all local branches
git add <file> - stage changes for the next commit 
git checkout <branch> - switch to an existing branch
git checkout -b <branch> - create and switch to a new branch
git commit -m "..." - commit staged changes with a message
fit remote add origin <url> - add remote repository under the name origin
git push -u origin <branch> - push branch to remote and set upstream tracking
git ls-remote --heads origin - list remote branches
mkdir -p docs- create documentation directory
cat << 'EOF' > docs/... - generate a file via here-document in the shell
