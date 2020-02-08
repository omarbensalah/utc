# Useful Terminal Commands

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
git commit -m "Initial commit"
git remote add origin git@github.com:<YOUR ACCOUNT>/<YOUR REPOS>.git
git push -u --force origin master
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