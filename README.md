[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/IyBZz2MB)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=15979059)
###### ICS3UC - Mr. J

# Using VSCode and GitHub

You are reading a Git _repository_ (aka repo). It is a package of files that have a history tracker. GitHub :octocat: is a place ("hub") to store Git repos online. You can download and edit the repo, then upload it back to GitHub for safe-keeping.<br>**Mr. J will demonstrate in class or read below if you miss the demo.**

## First - Set your user info for Git on your computer

Before you can use GitHub in your VSCode, you need to make sure your info is correct. **This only has to be done once (per computer)**.
1. If you don't see a terminal in the bottom, open one (Terminal > New Terminal)
2. Enter this: `git config --global user.name "Your Name"`   * use _your_ name, for example Mr. Jamieson
3. Not enter: `git config --global user.email "first.last@stu.ocsb.ca"`  * use _your_ email address for example mrj@stu.ocsb.ca

## Let's download this repo and edit it inside VSCode

You have two options that do the same thing.<br>
In both cases, you will need the web address (URL) of the repo you want to edit.

You have to close your current work in VSCode by going to **FILE > Close Folder** (don't worry, you can always open the folder again later)

### Option 1:
- Click on the **Source Control** menu on the left (CTRL+SHIFT+G keyboard shortcut)
- Click on **Clone Repository**
- In the panel that opens, paste the URL to the repository and hit ENTER
- You'll be asked where to save the code on your computer (_don't select "My Drive"_)
- You might be asked if you want to open the workspace - yes, click Open

### Option 2:
- Use the keyboard shortcut CTRL+SHIFT+P
- In the search panel that pops-up type **clone**
- Select **Git: Clone**
- Paste the URL to the repository and hit ENTER
- You'll be asked where to save the code on your computer (_don't select "My Drive"_)
- You might be asked if you want to open the workspace - yes, click Open

## Saving changes to your code

Your code will save to your local computer while you work, but the _history_ is not created automatically.

### Create a 'Snapshot' of the repo:

1. Go to the **Source Control** tab in VSCode
2. **Enter a commit message**  (it should reflect what changes have been made to the code.)
   - Simple messages like "Final edit" or "Fixed rounding error" are good.
3. In the heading titled **Changes** click the `+` to "Stage All Changes". This prepares the files for the snapshot.
4. Click **Commit**

This created a new snapshot of the code changes, in case you ever want to go back.

### Push (upload) your changes back to GitHub
After you commit, the `Commit` button should change to `Synch Changes` or something similar. Click that to upload your code to GitHub.

### [Your Task](./YOUR_TASK.md)  (click)

<br><br><br>
