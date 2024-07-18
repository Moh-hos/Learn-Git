# What is the Git folder and what does it do?

If you have used Git, you might have noticed the Git folder

This folder contains all the information we need to change the code in this path and it is necessary for Git to work

To understand how Git works, we need to pay attention to the list of folders that are in this directory

When we create a Git repository, this folder becomes the root of our project

Inside this folder, you will find various files and folders that contain information about your codebase

# the `head` file: keeping track of your current Branch

This file is a simple text file that contains HASH links that are currently committed in our repository.
This file is used to check the branch we are in and every time we change the branch, it automatically updates our commits.

# the `refs`: store commits and refreshes in the branch

This folder is where Git stores commits and branches in the repository. This folder contains different folders that correspond to different types of references.

For example, the head folder that refers to the head of your branch, or the tag folder contains information that you created special tags, or the remote folder for the branches that you shared.

# the `objects` folder: storing your code as a series of snapshots

This folder stores our codes as a set of snapshots

Each snapshot is the state of our code at a certain point in time
These snapshots are used to track our code changes over time
Inside this folder you will find two other folders
Info: Contains details about snapshots
Pack: Contains snapshots taken from our code

# the `config`: store configuration information for Git

The config file is where Git stores your configuration information for the repository

This file contains various settings that manage your default branch user email and new branches

# `hooks` folder :

The hooks folder is where, in addition to the shell scripts provided by Git, we can add new shell scripts to raise the standards of our code.
