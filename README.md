# Gittest

A new Flutter project with git testing

## Getting Started

This project is a starting point for a Flutter application.


1.  git init
2.  git remote add origin <remote name> 
2.1 git checkout -b <new branch name>
3.  git add .
4.  git commit -m "<commit name>"
5.  git push --set-upstream origin <branch name>

Additionals

- git remote -v (to check repo)
- git branch (to check where your branch)
- git checkout <branch name> (to change branch)
- git remote set-url origin <repo name> (to correct access right repo)

Generating SSH key and installing
- ssh-keygen -t ed25519 -C "aungmyintoo548@gmail.com" (OR) ssh-keygen -t rsa (OR) ssh-keygen
- pbcopy < ~/.ssh/id_ed25519.pub (OR) cat ~/.ssh/id_rsa.pub | pbcopy
  
A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
