# COM 421, Software Engineering
### Practice Task #2, Rewriting History

#### Requirements

1. Log into the AUCA server at `auca.xyz`.

2. Create a copy of your bare repository from Task #1.

        cp -r task_01.git task_02.git

3. Log out from the server.

4. Clone the new remote repository into the directory `task_02`.

Ensure that

* you have a Readme file starting from the first commit
* you have a proper `.gitignore` for all binary files at the end of the history
* you have a test specification file near the beginning of the history
* the next commit after that adds a skeleton of the string class with empty
  functions
* it is possible to compile the file at this stage with `make`
* you have a single commit for every function implementation after that
* it is possible to compile and run tests at every step
* the last commit is properly tagged

Use `git rebase` to fix any of those problems in your local repository.

Additionally, Use `git rebase` to

* rename at least one commit (excluding the last one)
* edit at least one commit (change at least one file)
* squash all ~4 commits created to implement functions from the string class
* drop one commit

#### Managing Sources

* Build all sources with `make`
* Remove compiled files with `make clean`
* Run test cases `./<test spec executable name>`

#### Essential Git Commands

* `git init`
* `git clone`
* `git add`
* `git status`
* `git commit`
* `git log`
* `git tag`
* `git push`
* `git rebase`

#### Submitting Your Work

Make sure that the repository history is in order by calling the `git log`
command. Try using `--stat` and `-p` options to check the state of every
commit.

1. Force push you local changes to the server. Note the problems that can arise
   from this operation.

2. Check the history of the `task_02.git` repository on the server.
