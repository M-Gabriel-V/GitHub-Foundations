# Cloning

We can clone 3 ways: HTTPS, SSH, GitHub CLI.

## HTTPS

The command is:
```sh 
git clone https://github.com/M-Gabriel-V/GitHub-Foundations.git 
```

### Note!
```If the repo is public, no credentials are needed to clone it.``` 

```BUT you will need credentials when pushing it back up.```

# Commits

# Branches

# Remotes

# Stashing

# Merging

# Git

Learning how to work with Git requires you to know the commands:

## How to create a git repository

```sh
git init
```
```Note - the repo will take everything into account in the current folder and child files.```

## Adding files to commit to the git repo

When you want to add all changes to the commit:
```sh
git add .
```
OR

When you want to add only a specific file to the commit:

```sh
git add file.extention
```

## Checking the status of file changes

When you want to know which files have been added to the commit or if there have been any changes whatsoever since the last commit:

```sh
git status
```


## Commiting changes to the repo

This will save all submited changes to the git repo, saving the commit as a node in the version controll tree. 

```sh
git commit
```


```Note - A selected IDE will be opened to allow you to write down detailed changes for the commit.```

---

### Best Practice
A best practice is for the commits to be simple and concise. They should be related to a single topic. This will improve tree readability and debugging process.

---

For the commit message, it is split into 2 parts: ```Title``` and ```Body```.

### Title
Short and concise.

If you cannot write a short and concise title, it is a sign that your commit contains more than one topic.

The title will be the one that will appear in the commit tree.

---

### Body
As detailed as possible.

It must include:
- what has been done
- what is different from before
- things to look out for

The body can be seen when accessing the commit itself.

---

### Fast Commit
If the change is minimal and does not require any detailed explanation, which can be refered only from the title, then the commit can be done faster:

```sh
git commit -m "Message"
```


# Markdown

Learning how to work in Markdown requires you to know the commands:

## ' # ' 
Is used for titles, sub-titles, sub-sub-titles and so on. The more '#' are added, the smaller the size of the content.

## ' ``` '
Must be added before and after the content. The content will be placed into a highlighted box.

```Example```

## ' ``` + sh '
It will create a box that allow the user to copy the contents with a click. Notation is important! Otherwise, it will turn into a simple ' ``` '. Check the raw .md to see the notation.
```sh
Example
```

## More to add...
