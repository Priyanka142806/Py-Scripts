![hacktober](https://miro.medium.com/max/1400/0*nuqEJFMVU_qIE2ZO)

# Py-SCRIPTS

![Contributors](https://img.shields.io/github/contributors/yagyandatta/Py-Scripts?color=darkgreen&style=plasitc)
![Forks](https://img.shields.io/github/forks/yagyandatta/Py-Scripts?color=blue&style=plasitc)

# Contribute to this documentation

Thank you for your interest in this project!

* [Introduction](#introduction)
* [How to contribute](#how-to-contribute)

## Introduction

This project aims to simplify and guide the learners towards the world of automation. All the scripts in this repository can be found under the ``scripts`` directory and have been contributed by our generous contributors. To add your contributions towards opensource community and grab the opportunity, Then lets start with this repository.
This repository consist a list of awesome `Terminal-Based` script projects.
If you are looking to make your contribution, follow the steps below.
</br>
If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/)

## How to contribute

This repository accepts all kinds of script contributions. Before making a contribution please make sure you have gone through our [contributing guidelines](https://github.com/yagyandatta/Py-Scripts/blob/master/.github/CONTRIBUTING.md).

<img align="right" width="300" src="https://user-images.githubusercontent.com/64744084/95018364-e7d2df00-067c-11eb-9989-5ed586adb11b.jpg" alt="fork this repository" />

## 1️⃣ Fork this repository to your account. </hr> </br>

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## 2️⃣ Clone the Repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

```
git clone "copied url"
```

## 3️⃣ Add a remote (upstream) to original project repository

```
cd <cloned-folder>
git remote add upstream https://github.com/[project_].git
```

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

## 4️⃣ Now synchronize your forked repo

It will help you to keep your forked repo updated with the original repo

```
git checkout main
git fetch upstream
git merge upstream/main
git push origin main
```

## 5️⃣ Now create a new branch

Now create a branch using the `git checkout` command:

```
git checkout -b your-new-branch-name
```

(The name of the branch does not need to have the word add in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## 6️⃣ Make necessary changes and commit those changes

Open the folder in your local code editor and add your changes or modifications

If you go to the project directory and execute the command `git status`, you'll see there are changes.

After making changes or modification on to your code locally, you need to add these files to the staging area. Add those changes to the branch you just created using the `git add` command:

```
git add --all
```

Once files added, you need to commit the changes to with an appropriate commit message using the `git commit` command:

```
git commit -m "<your-message>"
```

## 7️⃣ Push changes to GitHub

After committing the changes, you need to push the changes to master repo using `git push` command:

```
git push origin <your-created-branch-name>
```

replacing `<your-created-branch-name>` with the name of the branch you created earlier.

## 8️⃣ Submit your changes for review

Once you push the changes to your repository, the Compare & pull request button will appear in GitHub.</br>
Go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button
<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Type a proper description and give the PR an appropriate title. Finally, Open a pull request by clicking the `Create pull request` button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a `notification email` once the changes have been merged.

Congrats! You just completed the standard <b> fork -> clone -> edit -> pull request </b> workflow that you'll encounter often as a contributor!

<div>
<h1 align="center"> Thanks for your Contribution!! </h1>
</div>

<div align='center'>
<img style="float: center;" src=".github/images/1_IRGHmiGsa16stedQvIaZfw.gif" alt="submit pull request" />
</div>
