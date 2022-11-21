# Oneliners

<p align="center">
    📁 This repository contains Oneliners in any programming languages.
</p>

![GitHub contributors](https://img.shields.io/github/contributors/abedaton/oneliners)

## Important Notice:

The code we want should not be trivial and must be `usable` in a `useful` way.
For example, you can create a `calculator` that can be imported and used. Do not add hello world codes.
This project does not accept codes where only newlines or spaces were remove.
It also does not accept codes where a simple character was added to prevent going to a new line.
For example:
~~~py
import random; random.randint(0, 10)
~~~
is not the correct way in one line, but:
~~~py
__import__("random").randint(0, 10)
~~~
is !

### About
This repository contains codes that are written in a single line.

## Purpose
The purpose of this repository is to give a you some challenge, when I was a student, I loved writting stuff in one line and make it absolutely horrible to read. Hopefully, I am not alone !

## Contributing
For Contributing norms and guidelines, go to CONTRIBUTING.MD


## Adding Your Code:
Here are the steps:
1: Develop something in the programming language of your choice for any platform in less than #100LinesOfCode
2: Fork this repository
3: Clone this repository 
```
$ git clone "https://www.github.com/{Username}/100LinesOfCode.git"
```
where username is your GitHub account username.

4. Create a branch where you can do your local work.
Never work on **master** branch as we do not allow master commits except by admins.
```
$ git branch {branchname}
$ git checkout branchname
```

5. Do your work and stage your changes.
```
$ git add <filename>
```

6. Commit you changes with a commit message containing your name, file(s) worked upon, changes added.
```
$ git commit -m "Name| files| Changes"
```

7. Push changes to your forked repository
```
$ git push -u origin branchname
```

##### Synchronize forked repository with Upstream repository

1. Create upstream as our repository
```
$ git remote add upstream "https://github.com/josharsh/100LinesOfCode"
```

2. Fetch upstream changes in local machine
```
$ git fetch upstream
```

3. Switch to master branch
```
$ git checkout master
```

4. Merge changes in local machine
```
$ git merge upstream/master
```

5. Push changes to your forked GitHub repository
```
$ git push -f origin master
```

## Structure of Your Code:
The *root* directory of your developed application must contain
* A README.md describing your project, idea and Implementation
* Source code for your app
* An explanation of how to run your code

Note: Please Add Author's name in Readme.md of application. 
