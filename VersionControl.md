# Version Control

## Version control and you
What is version control? Version control is a way to track and manage your code as it changes over time.

What is the value that version control provides?
* History
    - It tracks changes in code so you can see how code evolves over time.
    - You can see what changes were made and when.
    - You can see who made what changes.
* Undo
    - At any point, you can go back to a previous checkpoint to see the code at that point in time.
* Teamwork
    - Version control provides branching, allowing multiple people to work on multiple versions of code at the same time.
    - To support branching, version control also provides the ability to merge branches, bringing the multiple versions back together into one.
* Tooling
    - Often, version control systems provide tooling to improve discussion about code and trigger events based on changes to code.

### Vocabulary
* Commit
    - A snapshot of your code and files at some point in time. It includes the code changes made, who made them, when they were made, and a message summarizing the changes, entered by the user.
* History
    - The collection of commits over time for a repository.
* Repository
    - A collection, usually a folder, of code treating as an individual unit with its own history.
* Branch
    - A version of a repository that maintains its own path of history while sharing history with other branches of the same repository
* Remote
    - A copy of a Git repository on another computer

## What are the differences between SVN and Git?
* Git is decentralized. Each copy is a full working copy. The copy of a repository on your laptop is the same as the copy on the server. This means you can commit while offline. You can sync up later. SVN is centralized. You must rely on the server to preserve your changes.
* Branching is easy. It's pretty easy in SVN as well, but branching is a first-class citizen in Git. It also handles remotes much easier.
* The tools are awesome. Github, BitBucket, and Gitlab provide excellent ways to collaborate on code and visualize history.
* Git is harder to learn. It is more flexible, and that means there are more things you need to learn and more possible ways to solve problems.

## First, let's learn the command line
### Windows
1. Open command line
    * You can be normal by opening `Command Prompt` from the Start Menu.
    * Or you can be fancy and use `Win + r` to open the run dialogue, input `cmd`, and hit enter
2. Practice navigating with `dir` and `cd`
    * Command line is just like browsing folders with Windows Explorer. It shows files and folders. You can enter and exit folders just the same.
    * The `dir` command shows the contents of the current directory. If you do `dir <some_folder>` where `<some_folder>` is a directory, it will show the contents of that directory.
    * The `cd` command is short for change directory. You can do `cd <some_folder>` to change your current location to `<some_folder>`. If you want to go up a folder, use `..`.
    * The `mkdir` command is short for make directory. You can enter `mkdir <some_path>` to create a folder at `<some_path>`.

### Mac
TBD
