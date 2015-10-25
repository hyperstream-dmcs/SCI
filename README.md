# SCI
This repository contains the code for an Android visitor app for the Science Center of Iowa.  This code is created and managed by the Des Moines Christian Hyperstream club.

## Git for Collaborators
### Github setup
1. Create an account at <github.com>
2. Contact Daniel Wright (dwwright1987) to give him your github username, and ask to be added as collaborator.

### Git setup
1. Download and install [Git](https://git-scm.com/).
2. Ensure Git is setup correctly by opening a command prompt and running "git --version".
  * If this does not work, add git installation location to your Path variable.
3. Configure git ssh:
  1. Open Git Bash
  2. Execute "ssh-keygen -t rsa" (Do not enter a filename or password)
  3. Copy contents of "C:\Users\<username>\.ssh\id_rsa" into Github account ssh settings
4. Setup git globla configs:
  1. From command prompt run -> git config --global user.name "John Doe"
  2. From command prompt run -> git config --global user.email johndoe@example.com
  
### Git flow
1. Fork <https://github.com/hyperstream-dmcs/SCI>
2. git clone git@github.com:[git-username]/SCI.git
3. git add upstream master git@github.com:hyperstream-dmcs/SCI.git
4. git checkout -b feature/<storie-name>
5. git commit (often while developing)
6. git push origin feature/<storie-name> (when developmnet is done)
7. Create pull request and get it reviewed and merged.
8. git checkout master
9. git pull upstream master
10. git push origin master
11. git branch -d feature/<storie-name>
12. git push origin --delete feature/<storie-name>
