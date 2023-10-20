
# Contribution Rules📚:

- Do NOT add any build steps e.g npm install (we want to keep this a simple static site)
- Do NOT remove other content.
- Styling/code can be pretty
- Try to keep pull requests small to minimize merge conflicts

## Getting Started 🤩🤗:

- Fork this repo (button on top)
- Clone on your local machine

```terminal
git clone git@github.com:your-uer-name/Meal-App.git
```

- Navigate to the project directory.

```terminal
cd lib
```

- Create a new branch with a sensible name like your-name-add-hover-icons

```markdown
git checkout -b my-new-branch
```

- Stage the changes

```markdown
git add .
```

- Commit your changes

```markdown
git commit -m "Relevant message"
```

- Then push

```markdown
git push origin my-new-branch
```

- Create a new pull request from your forked repository

## Avoid Conflicts {Syncing your fork}

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PRs may be merged while you're working on your branch/fork.

```terminal
git remote add upstream git@github.com:SiddheshMore24/Meal-App.git
```

You can verify that the new remote has been added by typing

```terminal
git remote -v
```

To pull any new changes from your parent repo run

```terminal
git merge upstream/main
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.
