### Command 0: `git status`

You can see all your change in your machine before any add (Stage).

### Command 1: `git clone`

You can clone any public repo at any server in your local machine.

### Command 2: `git add .`

After change your code you can add your code to "I have some changes over my
code, so please put them over the stage and add them as new changes!"

__Note__: You can use `git add file_name.extension` to select one or even
multiple files.

### Command 3: `git commit`

Commit can help you to add title and content as message of your change.

#### One line commit message

```bash
git commit -m "one line commit"
```

#### After following it will open your editor to write long message

```bash
git commit
```

![commit](./assets/images/Items.png)

### Command 4: `git push`

Send your code to your favorite server.

### Command 5: `git pull`

Download all remote changes over your local machine

__Note__: in some cases, you will need to do `git fetch --all`. This command
will fetch and sync all changes from all branches in your local machine.

### Command 6: `git merge`

Merge one branch to another branch. In following commands, merge master branch
with beta.

```bash
git checkout master
git merge beta
```

### Command 7: `git checkout a new branch`

```bash
git checkout -b new-branch-name
```

### Command 7-1: `git checkout branch-wip`

Switch between branches.

### Command 8: `git switch -c #commit_hash`

You can switch between your repo commit.

### Command 9: `git push --delete origin branch-name`

You can remove a branch from your remote server.

### Command 10: `git checkout -d branch-name`

Remove a branch from your local machine.

### Command 11: `git diff`

You can check all different between now and before.