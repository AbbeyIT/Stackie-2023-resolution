# Contributing

Hi Stackies! In order for you to add your resolution please **Add yourself** to the [list of stackies](Stackies.md) in **Alphabetical Order** along with your first pull request.

This document lays out how to get you started in contributing, so please read carefully and throughly.

If you have any concerns or the steps are unclarified to you, you can approach your concern in the [discussions](https://github.com/AbbeyIT/Stackie-2023-resolution/discussions/1).

---

## Steps

1. [Fork](https://help.github.com/articles/fork-a-repo/) this project

Click the fork button on the repo at [https://github.com/AbbeyIT/Stackie-2023-resolution](https://github.com/AbbeyIT/Stackie-2023-resolution)

2. [Clone](https://help.github.com/articles/fork-a-repo/#step-2-create-a-local-clone-of-your-fork) your forked version 

Your repo will now be in your GitHub. Clone the repo to your computer with the following command:
``` 
git clone https://github.com/<YOUR-GITHUB-USERNAME>/Stackie-2023-resolution.git
```
3. Switch to the cloned folder. 
```
cd Stackie-2023-resolution
```

4. Create a [branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches#working-with-branches)

Branch away from the `main` branch and use the following schema for naming your branches:

``` 
git checkout -b <ANY-NAME>
```

5. Make changes
- Open `STACKIES.md` file. 
- Add your details to the table with your name, github handle, and your resolution.
- Make sure to add your name in **Alphabetical Order**.

**Example Format** 

```
| [Name](GitHub-Link)                | Resolution                 |
| [Abbey](https://github.com/AbbeyIT) | To focus on my health more |
```

6. Staged your commit.

Add your changes to the `STACKIES.md` file with the following command:

``` 
git add STACKIES.md 
```

7. [Commit](https://help.github.com/articles/adding-a-file-to-a-repository-using-the-command-line/) your changes (write a short descriptive message of what you have done)

``` 
git commit -m "add <yourname> to Stackies"
```
If you are not sure how to make a good commit message, please read [here](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/).

8. [Push](https://help.github.com/articles/pushing-to-a-remote/) your changes to your forked version

Push your changes, use your branch name you created above

```
git push origin <BRANCH-NAME>
```

7. Go to the original project on GitHub & Create a [Pull Request](https://help.github.com/articles/about-pull-requests/)

You now will get a link in the terminal to create the pull request you can go to that link or go into your forked repo and create the pull request.

- On the GitHub website, navigate to your forked repo - on the top of the files section, you'll notice a new section containing a `Compare & Pull Request` button.

- Click on that button, this will load a new page, comparing the local branch in your forked repository against the main branch in the Stackie 2023 resolution repository. Fill up the necessary details there and click the green `Create Pull Request` button. 

- Your pull request will be reviewed and then eventually merged.

---

## How can I fix a merge conflict?

A GitHub conflict is when people make changes to the same area or line in a file. This must be fixed before it is merged to prevent collision in the main branch.

- **To read more about this, go to [GitHub Docs - About Merge Conflicts](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)**

- **To find out about how to fix a Git Conflict, go to [GitHub Docs - Resolve Merge Conflict](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github)**

- You can also  submit an issue in the [Issues](https://github.com/AbbeyIT/Stackie-2023-resolution/issues).

---

## Congratulations! 🥳
You have now created your first pull request to this repo and have your first contribution. On to more green squares! 🟩