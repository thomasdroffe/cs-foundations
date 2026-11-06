# Commands I have learned

## 6th of November 2026: Git Commands

git config --global user.name "NAME" :: Sets the name attached to my commits.
git config --global user.email "EMAIL" :: Sets the email attached to my commits (my GitHub private address).
git config --global init.defaultBranch main :: Makes new repos start on a branch called main.
git config --global core.editor nano :: Sets nano as the editor Git opens when it needs text from me.
ssh-keygen -t ed25519 -C "LABEL" :: Creates an SSH key pair (a private key and a public key).
cat ~/.ssh/id_ed25519.pub :: Prints my public key so I can paste it into GitHub.
ssh -T git@github.com :: Tests my SSH connection to GitHub without opening a login session.

## 5th of November 2026: Linux Commands

pwd :: Shows what directory you are in. 
cd :: Allows you to move between directories. 
ls :: Lists files (or directories) within a directory.
mkdir :: Used to create a directory.
cp :: Copies files between directories.
mv :: Renames files, as well as moves them between directories.
cat :: Displays the contents of files.
less :: Opens the contents of a file in an interactive viewer. Closed with 'q'. 
man :: Opens the manual for particular commands (if it has one). Closed with 'q'. 
