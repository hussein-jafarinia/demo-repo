#Demo

Some description!

## subheader

Watch tuorial on Youtube.

cloning the repo: in vscode terminal -> git clone https://github.com/hussein-jafarinia/demo-repo.git
changing directory to the cloned repo: in vscode terminal -> cd demo-repo
seeing every file in the cloned repo's directory: in vscode terminal -> ls -al
seeing the changes to files in the cloned repo: in vscode terminal -> git status
making every change to be tracked: in vscode terminal -> git add .
commiting the trakced changes: in vscode terminal -> git commit -m "Added index.html" -m "some description"
NOW IT'S TIME FOR CREATIG SSH KEY:
do everything that this link says in macOS terminal -> https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=linux
then ssh -T git@github.com in macOS terminal
then git remote set-url origin git@github.com:username/your-repository.git vscode terminal (assuming vscode terminal is the same directory as repo)