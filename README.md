

```sh

# Create a new repository on the command line
 
touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/c0ldlimit/vimcolors.git
git push -u origin master
 
# Push an existing repository from the command line
 
git remote add origin https://github.com/c0ldlimit/vimcolors.git
git push -u origin master

git push -f origin master

(base) ➜  .vim git:(master) git branch --set-upstream-to=origin/master master
Branch 'master' set up to track remote branch 'master' from 'origin'
```
