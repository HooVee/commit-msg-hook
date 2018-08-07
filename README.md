# commit-msg-hook
Git-hook for better commit messages

This hook checks your commit messages according to following rules:

- Subject line should be 50 characters long or less
- First letter in subject line is in upper-case
- Subject line should not end with period
- Subject line has more than one word in it
- Subject line is in imperative mood
- Second line is empty
- Description lines are 72 characters or less
- Description is more than one word long.

The hook accepts tags in front of the commit message, for example
if you want to specify part of the project the commit refers to.

Example: `git commit -m "[Products] Add new product model"`

Usage:

Clone this repository or just copy the file `commit-msg` to your project's 
git-hooks (`.git/hooks/`). *Remember to give it execution rights (chmod +x in Linux)*

Dependencies:

- Python
