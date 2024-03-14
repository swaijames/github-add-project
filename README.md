# github-add-project
How to add your project to GitHub at first time

## **setup github**

1: setup github username
  ```
    git config user.name
  ```
2: setup github email
```
    git config user.email
```
3: setup github password
```
    git config user.password
```

## **add projevt to github**
1: Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub.

 ![](https://miro.medium.com/v2/resize:fit:466/format:webp/1*9o8-S1mct_eAAZa7oC_XEw.png?raw=true)

2: Open Git Bash on your project location then initialize the local directory as git repository
```
git init
```
3: Add the files in your new local repository. This stages them for the first commit.
```
git add .

```
4: Commit the files that you’ve staged in your local repository.
```
git commit -m "first-commit"
```
5: At the top of your GitHub repository’s Quick Setup page, click to copy the remote repository URL.
![](https://miro.medium.com/v2/resize:fit:1100/format:webp/0*21avD5Wo40tKpDcR.png?raw=true)

6: In the Command prompt, add the URL for the remote repository where your local repository will be pushed.
```
git remote add origin your repository link 
 ```
7: Push the changes in your local repository to GitHub.
```
git push origin master
```
** Congrats !!! You did it **
