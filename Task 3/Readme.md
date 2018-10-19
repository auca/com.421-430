# COM 421, Software Engineering
### Practice Task #3, Git Branches and Remotes

Your task is to maintain a repository for a small C project from the archive
with another student. The archive has sources for a custom stack class with two
implementations (array and linked list stacks), test specifications, sample
programs to illustrate class usage, and a build file. Imagine that your are
working on this project from the beginning. You will get an assigned stack
implementation that you should maintain in your local repository. Inside of it
you have to maintain stable, development and topic branches. The work on a
specific stack implementation should go into the topic branch. At the end, merge
you work into the development branch, test it, and finally integrate it into the
stable `master` branch with an appropriate version tag.

As with the previous task you should start by creating a readme file with a
class description. Set a `.gitignore` with several appropriate patterns for a C
project. Add a test specification file with an outline and test cases for all
required functions. Create a skeleton of a stack class from the specification.
Add implementation for each function one by one. Test each function by compiling
and running test cases from the spec. Add each major (logically finished) part
of your work to the repository history. It is your job to decide which step to
record. At the end, tag the final version of the project.

Create a central bare repository in your home directory on a specified server.
You should only allow read access for the group `com-421-430` (for the `clone`
command to work). Ask another student to pull your implementation from there and
integrate it into his central repository. Do the same for a similar request from
another student. Get and integrate his/her implementation into your local
repository (the one that is NOT on the server). Push tagged changes to your
central repository.

#### Files

[Project Files](https://drive.google.com/open?id=0B85z_dQxOMgLc2Q2RU5UR1RHT3c)

#### Initial Steps

1. Unpack files from the archive into your working directory.
2. Create a directory for a new repository.
3. Go into a newly created directory.
4. Initialize a new repository.
5. Add at least one file and create an initial commit. Your current `master`
   branch should represent a stable state of your project.
6. Create and switch to a development branch. Use it to prepare integrations
   into the stable branch.
7. Create and switch to a topic branch. Name it after the assigned
   implementation.
8. Maintain the branch by adding implementation files step by step as it was
   previously described.
9. Switch to the development branch and merge your topic branch.
10. Check your work and switch to the stable branch. Merge development branch
    into the stable `master` branch.
11. Create a bare clone of a local repository.
12. Copy the bare repository to the specified remote server.
13. Set the remote in the local repository to the ssh path of the newly created
    remote repository.
14. Login into the remote server and set read permissions for the `task_03.git`
    directory for `others`.
15. Ask another student to pull and integrate changes from the newly created
    central repository.
16. Do the same for a similar request from another student. Pull and integrate
    a different stack implementation into your local repository.
17. Push changes with a new stack implementation merged into a stable branch to
    your central repository on the server.

#### Remotes

  `origin ssh://<your login name>@auca.space:/~/task_03.git`

  `<peer> ssh://<your login name>@auca.space:/home/<peer>/task_03.git`

  Where <peer> is the login name of another student.

#### Managing Sources

* Build all sources

  `make`

* Run test cases

  `./td_stack_test`

* Get usage information from a sample program.

  `./td_stack_sample`

* Run a sample program with parameters.

  `./td_stack_sample <parameter> <another parameter>`

* Remove compiled files

  `make clean`

#### Git Commands

* `git config`
* `git init`
* `git add`
* `git status`
* `git commit`
* `git log`
* `git tag`
* `git branch`
* `git checkout`
* `git reset`
* `git merge`
* `git rebase`
* `git clone`
* `git remote`
* `git fetch`
* `git pull`
* `git push`

#### Unix Commands

* `ssh`
* `scp`
* `chmod`
* `chown`

#### Getting Help

Book

* [Pro Git](http://git-scm.com/book/en/v2/)

Manual Pages

* `git help <command>`
* `git <command> --help`
* `man git-<command>`
* `man <unix program>`

#### Submitting Your Work

Ensure that your central repository on the server has stable, development, and
topic branches. Check that all solutions were integrated into the stable branch
at some point.
