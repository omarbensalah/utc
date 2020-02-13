# Useful Terminal Commands

## BASH

Create a script
```
touch <SCRIPT_NAME>.sh
chmod +x <SCRIPT_NAME>.sh
echo '#!/bin/bash' > <SCRIPT_NAME>.sh
```

Run a script
```
./<SCRIPT_NAME>.sh
```

## CHOWN

Change ownership
```
sudo chown -R <USER> <DIRECTORY>
```

## GIT

Clear Git history
```
rm -rf .git
git init
git add .
git commit -m "<MESSAGE>"
git remote add origin git@github.com:<YOUR ACCOUNT>/<YOUR REPOS>.git
git push -u --force origin master
```

Keep a fork up to date
```
git clone git@github.com:<YOUR ACCOUNT>/<YOUR REPOS>.git
cd <YOUR REPOS>/
git remote add upstream git://github.com/<THEIR ACCOUNT>/<THEIR REPOS>.git
git fetch upstream
git merge upstream/master <BRANCH>
```

## JEKYLL

Start project after cloning
```
bundle install --path vendor/bundle
bundle exec jekyll serve
```

## SSH

Generate new SSH Key
```
ssh-keygen -o
cat ~/.ssh/id_rsa.pub
```